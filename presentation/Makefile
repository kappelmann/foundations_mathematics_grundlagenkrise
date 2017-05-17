BUILD_DIR=build
TARGET=Presentation_Foundations_Mathematics_Foundational_Crisis

.PHONY: all clean watch

OPTIONS=-gg -bibtex -auxdir=$(BUILD_DIR) -outdir=$(BUILD_DIR) -pdf

all:
	latexmk $(OPTIONS) $(TARGET).tex && cp $(BUILD_DIR)/$(TARGET).pdf .

clean:
	rm -rf $(BUILD_DIR)/*
