## stonks 

firstly, i logged into `nc mercury.picoctf.net 27912 `
\
then to get the API token i typed `%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x%x`
\
then went to a hex editor and typed the token i got 
\
it gave some text which contained the flag but wasnt properly arrnaged. I deleted the extra piece of information and used 'swap endiannes' to get the flag properly.

![Screenshot 2023-11-14 at 4 43 02 PM](https://github.com/ArnDev7/picoCTF_writeup/assets/148140634/fda4f76f-0eab-4c8d-a6bb-a051c7ece820)

flag: **picoCTF{I_l05t_4ll_my_m0n3y_1cf201a0}**

---