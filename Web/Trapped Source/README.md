![image](https://user-images.githubusercontent.com/63996033/227574492-e4e0a9f2-83b7-4c7c-b73e-3aaa7cc12eb7.png)

Spawning the docker leads us to a website, that requires us to key in a pin to get the flag.

![image](https://user-images.githubusercontent.com/63996033/227574799-637d090b-0486-4396-8774-c0261b214e63.png)

Checking the source, I found that it checks the pin against `CONFIG.correctPin`

![image](https://user-images.githubusercontent.com/63996033/227574973-dcc53ad0-3aed-44ff-b0e5-014a88f74f02.png)

So, going to the console, I found the pin, and used it to get the flag.

![image](https://user-images.githubusercontent.com/63996033/227575146-a8f6a85a-ff0b-405c-a76d-4b04b8a57cf6.png)

![image](https://user-images.githubusercontent.com/63996033/227575235-70387dc1-e0c0-4276-8a8d-edb89e3e8057.png)

![image](https://user-images.githubusercontent.com/63996033/227575284-4075051a-4d15-4f9f-a995-e81bcf78b210.png)

![image](https://user-images.githubusercontent.com/63996033/227575406-a4e24493-bdf5-4778-9461-4455c116cd64.png)

Flag: HTB{V13w_50urc3_c4n_b3_u53ful!!!}
