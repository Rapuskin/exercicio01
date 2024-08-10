[<h4 align="center">
⬇️ * # Exercicio01 # * ⬇️
</h4>
<h4 align="center">
  * Exercicio01_CICD_Impacta: *
</h4>

<h4>
  ! CONFIGS INICIAIS !
<h4> 
   R: 
<h4>
</h4>
</h4>
</h4>
<h4>


 
![image](![alt text](![image](https://github.com/user-attachments/assets/36f4a9f6-6413-420c-b388-2ce5e851334c)


A) No working dir, executar o comando:
   echo 01 > arquivo.txt
<h4> 
   R: 
<h4>   
</h4>
</h4>
</h4>
<h4>


![image](![alt text](image-1.png))


B) Adicionar o arquivo no staging e conferir o status:
<h4> 
 R: 
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git add .
</h4>
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git status
</h4> 
<h4>
</h4>
</h4>
</h4>
<h4>



![image](![alt text](![image](https://github.com/user-attachments/assets/c39a5aa0-3c20-481b-a65f-0e91b35dfb0a)
))


C) Commitar o arquivo do staging com a descrição "git add example - arquivo.txt":
<h4> 
R:
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git commit -m "git add example - arquivo.txt" .
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>


![image](![alt text](![image](https://github.com/user-attachments/assets/cdecb479-63e7-4581-9878-dc15ca774f37)
))


D) Sobrescrever o conteúdo do arquivo.txt:
   echo 02 > arquivo.txt
<h4> 
R:
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ echo 02 > arquivo.txt
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>

![image](![alt text](![image](https://github.com/user-attachments/assets/e5c8c25f-4d47-428b-a9d6-fce4f1771024)
))


E) Verificar o diffing no arquivo:
<h4> 
R: 
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git diff
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>



![image](![alt text](![image](https://github.com/user-attachments/assets/e83b2e16-b105-4e58-ade5-82ef231bd566)
))



F) Adicionar novamente o arquivo no staging e conferir o status:
<h4>
R: 
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git add .
</h4>
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git status
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>

![image](![alt text](![image](https://github.com/user-attachments/assets/1368cb43-150f-451b-ab74-084228351dc7)
))


G) Verificar o diffing no arquivo:
<h4> 
R: 
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git diff
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>




H) Sobrescrever o conteúdo do arquivo.txt:
 echo 03 > arquivo.txt
<h4>
R: 
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ echo 03 > arquivo.txt
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>


![image](![alt text](![image](https://github.com/user-attachments/assets/d6f3ef38-343a-4523-a55c-700906600afb)
))


I) Verificar o diffing no arquivo:
<h4>
R: 
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git diff
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>



![image](![alt text](![image](https://github.com/user-attachments/assets/3b55b560-9778-42e2-8370-19fd60cc7f2e)
))


J) Fazer o restore do arquivo da área de staging e verificar o status:
<h4>
R: 
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git restore arquivo.txt 
</h4>
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git status
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>


![image](![alt text](![image](https://github.com/user-attachments/assets/c238395c-c134-4983-8aef-5682b0c61e30)
))


K) Realizar o commit do arquivo e verificar o log:
<h4>
R: 
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git commit -m "Primeiro Commit - Arquivo.txt"
</h4>
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git log
<h4>
</h4>
</h4>
</h4>
<h4>

![image](![alt text](![alt text](![image](https://github.com/user-attachments/assets/8e0630b3-0af6-43c0-bd89-9026b7696d52)
)))

![image](![alt text](![alt text](![image](https://github.com/user-attachments/assets/a135c039-3cdc-4aed-86e7-b65b02364ad7)
)))


L) Adicionar um arquivo gitignore com o seguinte conteúdo:
 *.txt
<h4> 
R: 
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ vi .gitignore
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>

![image]![alt text](![image](https://github.com/user-attachments/assets/94e66768-6471-4ec6-9b85-6042f9487391)
))


M) Criar um arquivo novo.txt e verificar o status:
<h4> 
R:
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ echo > novo.txt
</h4>
<h4>
@Rapuskin ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ echo > git status
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>

![image](![alt text](![image](https://github.com/user-attachments/assets/c924f116-d2d0-48ca-90de-edd834340557)
))
](https://github.com/user-attachments/assets/36f4a9f6-6413-420c-b388-2ce5e851334c)
