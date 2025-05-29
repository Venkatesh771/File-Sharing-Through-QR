<h2 align="center">Secure File Sharing Through QR - (One Time Link Generator) <img align="center" src="https://cdn-icons-png.flaticon.com/512/12393/12393250.png" alt="venkatreddy" height="30" width="30" /></h2>
<h3>A secure and simple file sharing system that uses QR codes and one-time expiring links. Built using Spring Boot(Java) for the backend and React + Tailwind CSS for the frontend.</h3>

![Page_1_GitHub](https://github.com/user-attachments/assets/e11c1064-852d-4c23-ac41-593c0282dcc7)
![Page_2_GitHub](https://github.com/user-attachments/assets/30930398-abef-4e36-ba14-36ae4c5d4f2f)

## Features <img align="center" src="https://cdn-icons-png.flaticon.com/512/6954/6954401.png" alt="venkatreddy" height="30" width="30" />

- Upload files up to 5GB
- Generate one-time download links
- Expiry timer (15 min, 1 hour, 24 hours)
- Auto-delete files after access or timeout
- Share files via QR code or copyable link
- No sign-up or login required
- Mobile-friendly interface

---
<h3 align="center">Tech Stack</h3>

## Front-End
- React
- Tailwind CSS
- Axios
- QR Code Generator (`qrcode.react`)
- Countdown Timer

## Back-End
- Java 17
- Spring Boot
- Spring MVC
- File system storage
- UUID & Token-based access
- Expiry scheduler with `@Scheduled`

## Security Notes
- Files are stored temporarily and deleted after access/timeout.
- Each download link is single-use only.
- QR links are random and tokenized.
