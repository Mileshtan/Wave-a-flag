# Wave-a-flag
Cylab CTF Wave a flag

Q: Can you invoke help flags for a tool or binary? This program has extraordinarily helpful information... warm

Hint1: This program will only work in the webshell or another Linux computer.

Hint2: To get the file accessible in your shell, enter the following in the Terminal prompt: $ wget <URL here>, where the url can be found in the details section.

Hint3: Run this program by entering the following in the Terminal prompt: $ ./warm, but you'll first have to make it executable with $ chmod +x warm

Hint4: -h and --help are the most common arguments to give to programs to get more information from them!

Hint5: Not every program implements help features like -h and --help.

Step1: Goto terminal (linux only) and type wget <link>
Note: wget will download the file from the link.

<img width="541" height="617" alt="image" src="https://github.com/user-attachments/assets/55d408e5-b7d5-465e-809a-b61fcaff4acc" />

Step2:  chmod +x <filename>
eg:  chmod +x warm
Note: It make the file warm executable. No changes will be seen in terminal

Step3: ./<filename>
eg: ./warm
Note: This command will execute the file.

<img width="523" height="259" alt="image" src="https://github.com/user-attachments/assets/6c9c4942-2a10-4182-b389-94cf77648f9b" />

Step4: Type ./warm -h

<img width="544" height="280" alt="image" src="https://github.com/user-attachments/assets/216b79ca-8e88-4e51-92ea-ab198bf5b982" />

Step5: Final answer: academy{b1scu1ts_4nd_gr4vy_57d8c79}


