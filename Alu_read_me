## Read-me
## Files required ot be downloaded beforehand:
IMT2022035_ALU_WITHOUT_ERRORS.v


## Explaining how the error were found in the code:
        1)As I compiled the file for the first time It showed a long list of errors.
        Thefirst error was shown to be at line 47 but I could find no erros.Then I realised that it may be due to something being not closed as was found with case.
        We needed to put an endcase to close it before endmodule.
        2)I ran the code again after saving it , but it still showed a syntac error at line 47.
        I realised that there may be another error present in the vicinity.
        As we all know, in verilog a multiline code needs to have a begin and an end but I realised that it was present here.
        I applied the changes and compiled it again.
        3)Now it showed I give up near line 84 so I went there.
        I saw that the begin had no end there so I placed an end there.
        4)It showed a very long list of errors saying ALU_Result is a wire here.
        I read the code and realised it was meant to be used as a reg.
        5)Now it showed an error saying that B was a wire.
        I saw the code and realised it was meant to be used as a reg.
        Also from the above code for the logic, I had seen that Carryout was meant to be used as a wire so I replaced that too.
        6)It showed only 2 errors now.
        1st one was in $dumpvars.
        I saw that the name was not given correctly for tb_alu.
        I corrected that.
        7)Now it showed only 1 error in the for loop where I saw that a random variable k was placed.
        I replaced it with i for the code to work correctly.
        
        
    


### Author-
    Sanchit Kumar Dogra
    IMT2022035
    Github-(Sanchit-Kumar-Dogra)
