# Makefile for LaTeX Resume

LATEX = pdflatex
SOURCE = resume.tex
OUTPUT = resume.pdf
BUILD_DIR = build
FINAL_PDF = ../Luann_Luna_Senior_iOS_Resume.pdf

.PHONY: all pdf clean

# Default target
all: pdf

# Build the PDF
pdf:
	@echo "Building resume PDF..."
	@mkdir -p $(BUILD_DIR)
	@$(LATEX) -output-directory=$(BUILD_DIR) -interaction=nonstopmode $(SOURCE) > /dev/null 2>&1 || \
		(echo "First pass completed with warnings (expected)"; true)
	@$(LATEX) -output-directory=$(BUILD_DIR) -interaction=nonstopmode $(SOURCE) > /dev/null 2>&1 || \
		(echo "Second pass completed"; true)
	@if [ -f $(BUILD_DIR)/$(OUTPUT) ]; then \
		cp $(BUILD_DIR)/$(OUTPUT) $(FINAL_PDF); \
		echo "Success! PDF generated at:"; \
		echo "  - $(BUILD_DIR)/$(OUTPUT)"; \
		echo "  - $(FINAL_PDF)"; \
	else \
		echo "Error: PDF generation failed. Check $(BUILD_DIR)/resume.log for details."; \
		cat $(BUILD_DIR)/resume.log; \
		exit 1; \
	fi

# Clean build artifacts
clean:
	@echo "Cleaning build artifacts..."
	@rm -rf $(BUILD_DIR)
	@rm -f $(FINAL_PDF)
	@echo "Clean complete."

# Show build log (useful for debugging)
log:
	@if [ -f $(BUILD_DIR)/resume.log ]; then \
		cat $(BUILD_DIR)/resume.log; \
	else \
		echo "No build log found. Run 'make pdf' first."; \
	fi

# Help target
help:
	@echo "Available targets:"
	@echo "  make pdf    - Build the resume PDF (default)"
	@echo "  make clean  - Remove all build artifacts"
	@echo "  make log    - Display the build log"
	@echo "  make help   - Show this help message"
