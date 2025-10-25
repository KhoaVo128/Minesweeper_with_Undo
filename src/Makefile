.PHONY: all clean run

all:
	javac gui/panel/*.java gui/*.java logic/*.java main/*.java
#-d $(OUT_DIR) $<

clean:
	rm gui/*.class
	rm gui/panel/*.class
	rm logic/*.class
	rm main/*.class

run:
	make all
	java main.Main
	make clean

