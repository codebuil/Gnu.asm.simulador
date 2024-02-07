.intel_syntax noprefix
.include "./file/base.s"

hellos: .asciz "hello world...\0"
kernel_main:
          call clears        
          mov ebx,offset x
          mov eax,10
          mov [ebx],eax
          mov ebx,offset y
          mov [ebx],eax               
          mov esi,offset hellos
          mov edi,0xb8000
          mov ecx,13                
          mov eax,0
          mov edx,2  
          call print32
               
                          
                          
                          
          EXITDO:                
                                    
                                    
                    EXIT:          
 
                
          jmpps:
jmp jmpps



