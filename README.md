# ALEO BLOCKCHAIN WORKSHOP 1 
## Deployment Link: https://explorer.aleo.org/transaction/at1t0asqhpwl3kp60p05ze52pd2frjfal78vgmkq06qkea24pvcd5qq2qsfrn
### Deployment ID: at1t0asqhpwl3kp60p05ze52pd2frjfal78vgmkq06qkea24pvcd5qq2qsfrn
#### Description of Steps Used
For my second_leo, I wrote the following code accordingly:
- leo new freddy_kodes_hello1: This was to create my project
- cd freddy_kodes_hello1: To change directory to current working directory
- Changed the private key in the .env file to the private key in my leo wallet
- leo run 2u32 3u32 --network testnet: This was to add the two numbers which gave us 5u32. u32 is the datatype
- leo deploy --network testnet: This made it possible for us to see the changes/activities on our leo wallet

##### Screenshot
![Screenshot (913)](https://github.com/user-attachments/assets/4662df35-7ef2-4e13-94f7-7ffe2d7f939b)

# ALEO BLOCKCHAIN WORKSHOP 2
## Deployment Link: https://explorer.aleo.org/transaction/at1uq2shxcwcl5nz0f5jgzcr9ncfcweq7tv8tudze8ufrrg4ep3xsxqmkh25t
### Deployment ID: at1uq2shxcwcl5nz0f5jgzcr9ncfcweq7tv8tudze8ufrrg4ep3xsxqmkh25t
#### Description of Steps Used
For my leo_project_token, I Wrote the codes using the following
- ../ to go to the previous directory
- cd my_project_name: To change directory to current working directory
- Changed the private key in the .env file to the private key in my leo wallet
- leo run mint <my_aleo_address> <amount>u64; e.g leo run mint aleo1fgftssyjrxh58gcw5ngnre7ttp6s5h9h70l93ltlkmmdmza58yxsdctefv 100u64
- leo run transfer "<Token_Record>" <to_address> <amount>u64
- We were  able to use the generated record from 1st command to input into the second command's first input and then our to address and amount
- leo deploy --network testnet

##### Screenshot
![Screenshot (919)](https://github.com/user-attachments/assets/dd319383-ec3d-43da-8103-0c24f7697f0a)
![Screenshot (920)](https://github.com/user-attachments/assets/4e061ce2-d692-4b72-b017-ae5acbedf17e)

# ALEO BLOCKCHAIN WORKSHOP 3
## Deployment Link: https://explorer.aleo.org/transaction/at1uc522zjljnvvfhq0jn95swsngzreakylnwu597npuwt3vm5cvg9s7qr457
### Deployment ID: at1uc522zjljnvvfhq0jn95swsngzreakylnwu597npuwt3vm5cvg9s7qr457
#### Description of Steps Used
For my aleo_voice_2, I Wrote the codes using the following
- ../ to go to the previous directory
- cd my_project_name: To change directory to current working directory
- Changed the private key in the .env file to the private key in my leo wallet
- leo run combine_hash_owner_receiver my leo wallet address receivers leo wallet address;
- example: leo run combine_hash_owner_receiver aleo1fgftssyjrxh58gcw5ngnre7ttp6s5h9h70l93ltlkmmdmza58yxsdctefv aleo1ce7wf7chgd5cywajg589z7mv433t8ua26h6dslfmgw2jgj02hvrs6qp8cm
- leo deploy --network testnet

##### Screenshot
![Screenshot (921)](https://github.com/user-attachments/assets/49bf9565-b317-428f-bb67-e87bfcff49e0)
![Screenshot (922)](https://github.com/user-attachments/assets/9c20c86f-2572-4d4f-8d6c-4bdea94b99a7)


