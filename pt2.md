I had the ip from the macine: it shows it on login
used dirb to find directories and found a weird directory 
![vuln2](https://user-images.githubusercontent.com/112130143/199201718-41704b24-67db-447d-b02b-8e7da422ff55.png)
looked to be a encrypted code so i googled it 
![vuln3](https://user-images.githubusercontent.com/112130143/199201737-0cd878d1-c815-41b9-98fd-10a3b11ac96c.png)
Got a code back
![vuln4](https://user-images.githubusercontent.com/112130143/199201760-a6a26c16-2f41-4cd4-9591-1e6ca5489d2c.png)
Used it in a directory that had a login
![vuln5](https://user-images.githubusercontent.com/112130143/199201779-25c885d7-ba4a-47e0-b37d-54795bcd2e78.png)
 Bruteforced the username with hydra
![vuln6](https://user-images.githubusercontent.com/112130143/199202424-76f2ffdf-a43f-426b-a989-a28e1ae42349.png)
 Got access to the server and terminal
![vuln7](https://user-images.githubusercontent.com/112130143/199202452-7492233b-8809-444c-8b42-973e0593f173.png)
