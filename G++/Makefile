# GNU Make solution makefile autogenerated by Premake
# Type "make help" for usage help

ifndef config
  config=debug64
endif
export config

PROJECTS := KarstSynthesis

.PHONY: all clean help $(PROJECTS)

all: $(PROJECTS)

KarstSynthesis: 
	@echo "==== Building KarstSynthesis ($(config)) ===="
	@${MAKE} --no-print-directory -C . -f KarstSynthesis.make

clean:
	@${MAKE} --no-print-directory -C . -f KarstSynthesis.make clean

help:
	@echo "Usage: make [config=name] [target]"
	@echo ""
	@echo "CONFIGURATIONS:"
	@echo "   debug64"
	@echo "   release64"
	@echo ""
	@echo "TARGETS:"
	@echo "   all (default)"
	@echo "   clean"
	@echo "   KarstSynthesis"
	@echo ""
	@echo "For more information, see http://industriousone.com/premake/quick-start"
