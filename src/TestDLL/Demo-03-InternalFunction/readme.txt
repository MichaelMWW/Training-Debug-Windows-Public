1. cl /Zi testunc.cpp /link dbghelp.lib
2. Find the matched pdb symbol and copy it to the same folder as the TestInternalFunctionCall.exe.
3. Run the command to set the _NT_SYMBOL_PATH in the command line. set _NT_SYMBOL_PATH=srv*c:\<ptah_to_TestInternalFunctionCall.exe>*http://symweb


Tried merge this cpp file to project, compile failed.
Due to: bret = SymFromName(hp, L"TestDLL!Add_Internal", pSymbol);
�ڶ�������˵������wchar_t��confuse����Ҫ�Ƚϱ������������Ҫ�����Թ�