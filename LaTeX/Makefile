# Makefile for LaTeX Resume (Bilingual: English + Portuguese)

LATEX = pdflatex
BUILD_DIR = build

# Source files
SOURCE_EN = resume-en.tex
SOURCE_PT = resume-pt.tex
SOURCE_V2_PT = resume-v2-pt.tex

# Output files in build directory
OUTPUT_EN = resume-en.pdf
OUTPUT_PT = resume-pt.pdf
OUTPUT_V2_PT = resume-v2-pt.pdf

# Final output files in root
FINAL_EN = ../Luann_Luna_Resume_EN.pdf
FINAL_PT = ../Luann_Luna_Resume_PT.pdf
FINAL_V2_PT = ../Luann_Luna_Resume_V2_PT.pdf

.PHONY: all en pt v2-pt clean log help

# Default target - build both versions
all: en pt

# Build English version
en:
	@echo "Building English resume PDF..."
	@mkdir -p $(BUILD_DIR)
	@$(LATEX) -output-directory=$(BUILD_DIR) -interaction=nonstopmode $(SOURCE_EN) > /dev/null 2>&1 || \
		(echo "First pass completed with warnings (expected)"; true)
	@$(LATEX) -output-directory=$(BUILD_DIR) -interaction=nonstopmode $(SOURCE_EN) > /dev/null 2>&1 || \
		(echo "Second pass completed"; true)
	@if [ -f $(BUILD_DIR)/$(OUTPUT_EN) ]; then \
		cp $(BUILD_DIR)/$(OUTPUT_EN) $(FINAL_EN); \
		echo "Success! English PDF generated at:"; \
		echo "  - $(BUILD_DIR)/$(OUTPUT_EN)"; \
		echo "  - $(FINAL_EN)"; \
	else \
		echo "Error: English PDF generation failed. Check $(BUILD_DIR)/resume-en.log for details."; \
		cat $(BUILD_DIR)/resume-en.log; \
		exit 1; \
	fi

# Build Portuguese version
pt:
	@echo "Building Portuguese resume PDF..."
	@mkdir -p $(BUILD_DIR)
	@$(LATEX) -output-directory=$(BUILD_DIR) -interaction=nonstopmode $(SOURCE_PT) > /dev/null 2>&1 || \
		(echo "First pass completed with warnings (expected)"; true)
	@$(LATEX) -output-directory=$(BUILD_DIR) -interaction=nonstopmode $(SOURCE_PT) > /dev/null 2>&1 || \
		(echo "Second pass completed"; true)
	@if [ -f $(BUILD_DIR)/$(OUTPUT_PT) ]; then \
		cp $(BUILD_DIR)/$(OUTPUT_PT) $(FINAL_PT); \
		echo "Success! Portuguese PDF generated at:"; \
		echo "  - $(BUILD_DIR)/$(OUTPUT_PT)"; \
		echo "  - $(FINAL_PT)"; \
	else \
		echo "Error: Portuguese PDF generation failed. Check $(BUILD_DIR)/resume-pt.log for details."; \
		cat $(BUILD_DIR)/resume-pt.log; \
		exit 1; \
	fi

# Build Portuguese V2 version (Sebratec current position)
v2-pt:
	@echo "Building Portuguese V2 resume PDF (Sebratec)..."
	@mkdir -p $(BUILD_DIR)
	@$(LATEX) -output-directory=$(BUILD_DIR) -interaction=nonstopmode $(SOURCE_V2_PT) > /dev/null 2>&1 || \
		(echo "First pass completed with warnings (expected)"; true)
	@$(LATEX) -output-directory=$(BUILD_DIR) -interaction=nonstopmode $(SOURCE_V2_PT) > /dev/null 2>&1 || \
		(echo "Second pass completed"; true)
	@if [ -f $(BUILD_DIR)/$(OUTPUT_V2_PT) ]; then \
		cp $(BUILD_DIR)/$(OUTPUT_V2_PT) $(FINAL_V2_PT); \
		echo "Success! Portuguese V2 PDF generated at:"; \
		echo "  - $(BUILD_DIR)/$(OUTPUT_V2_PT)"; \
		echo "  - $(FINAL_V2_PT)"; \
	else \
		echo "Error: Portuguese V2 PDF generation failed. Check $(BUILD_DIR)/resume-v2-pt.log for details."; \
		cat $(BUILD_DIR)/resume-v2-pt.log; \
		exit 1; \
	fi

# Clean build artifacts
clean:
	@echo "Cleaning build artifacts..."
	@rm -rf $(BUILD_DIR)
	@rm -f $(FINAL_EN) $(FINAL_PT) $(FINAL_V2_PT)
	@echo "Clean complete."

# Show build log (useful for debugging)
log:
	@echo "=== English Resume Log ==="
	@if [ -f $(BUILD_DIR)/resume-en.log ]; then \
		cat $(BUILD_DIR)/resume-en.log; \
	else \
		echo "No English build log found."; \
	fi
	@echo ""
	@echo "=== Portuguese Resume Log ==="
	@if [ -f $(BUILD_DIR)/resume-pt.log ]; then \
		cat $(BUILD_DIR)/resume-pt.log; \
	else \
		echo "No Portuguese build log found."; \
	fi
	@echo ""
	@echo "=== Portuguese V2 Resume Log ==="
	@if [ -f $(BUILD_DIR)/resume-v2-pt.log ]; then \
		cat $(BUILD_DIR)/resume-v2-pt.log; \
	else \
		echo "No Portuguese V2 build log found."; \
	fi

# Help target
help:
	@echo "Available targets:"
	@echo "  make all    - Build both English and Portuguese PDFs (default)"
	@echo "  make en     - Build English PDF only"
	@echo "  make pt     - Build Portuguese PDF only"
	@echo "  make v2-pt  - Build Portuguese V2 PDF (Sebratec current position)"
	@echo "  make clean  - Remove all build artifacts"
	@echo "  make log    - Display build logs for all versions"
	@echo "  make help   - Show this help message"
