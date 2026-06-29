# GPO Configuration

<img width="1223" height="772" alt="GPO - Disable Control Panel" src="https://github.com/user-attachments/assets/df209adc-87c0-452a-be30-34524f3bab0e" />

Two policies have been created for the HR group alone - a set desktop wallpaper and the restricted use of Control Panel. 
Only users in the HR group have these restrctions, while the IT group has the Windows default wallpaper and full Control Panel access

# Verification
<img width="1699" height="949" alt="HR - GPO Verification" src="https://github.com/user-attachments/assets/ff602722-7a78-47e6-a22d-0f13c17ec0f7" />
- Logged in as Sister (HR) and attempt to open Control Panel is denied. gpresult /r output posted

<img width="1706" height="950" alt="IT - GPO Verification" src="https://github.com/user-attachments/assets/45f3272e-8cd7-4b58-8f42-06a8126b75b4" />
- Logged in as Jane (IT) with full access to Control Panel. gpresult /r output posted
