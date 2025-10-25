# petAdoptionProject
# 🐾 Pet Adoption Center Management System

A full-stack database management system for a pet adoption center. This project allows users to manage pets, adopters, adoptions, staff, donations, and medical records using a PostgreSQL database, with optional frontend integration for image uploads and browsing.

---

## 📌 Features

- 🐶 Store and manage pet details 
- 👨‍👩‍👧 Track adopters and adoption records
- 💰 Manage donations and donor records
- 👨‍⚕️ Maintain staff and medical history for pets
- 🖼️ Upload and display pet images using Supabase storage 
- 🧾 Designed with third normal form (3NF) in mind

---

## 🧰 Technologies Used

- **PostgreSQL** – Core relational database
- **pgAdmin** – GUI for managing the database
- **Supabase** – For image upload and public URL hosting 
- **React** – Frontend interface 
- **Node.js / Express** – Backend API 

---

## 🗃️ Database Schema

### Key Tables:
- `pets` – Pet info including image URL
- `adopters` – People adopting pets
- `adoptions` – Adoption records (linking pets and adopters)
- `staff` – Staff managing the center
- `donations` – Records of donors and amounts
- `medical_records` – Medical history of pets

### Normalization:
- The database is normalized up to **3NF** to reduce redundancy and maintain data integrity.

---

## 🖼️ Image Upload Feature 

 using Supabase for image upload:

1. Create a bucket in Supabase
2. Upload images from your frontend
3. Store public URLs in the `pets.image_url` field
4. Display the image using `<img src={image_url} />`

---


<img width="3222" height="2396" alt="physical_schema" src="https://github.com/user-attachments/assets/f59d2c39-2c71-4dad-ba26-79fb78b4731e" />
![logical_schema](https://github.com/user-attachments/assets/63215253-ea59-407d-9d7d-af1d411ffb99)
![logical_schema (1)](https://github.com/user-attachments/assets/c698b9bc-e2d5-4347-ba53-77b13557a990)
![ER_Diagram](https://github.com/user-attachments/assets/4b001a91-ff39-489b-a091-68b35b1e2ddc)
<img width="1728" height="1117" alt="1" src="https://github.com/user-attachments/assets/a3561d32-3633-43a7-a27e-513d5fe3a4d4" />
<img width="1728" height="1117" alt="8" src="https://github.com/user-attachments/assets/e3085e9d-744c-4f38-89da-3d21787dd9e1" />
<img width="1728" height="1117" alt="9" src="https://github.com/user-attachments/assets/a2322038-15f0-4f40-ac98-b4495cb8d393" />
<img width="1728" height="1117" alt="2" src="https://github.com/user-attachments/assets/8d21eadf-1918-4a56-944d-f825e12d2140" />
<img width="1728" height="1117" alt="6" src="https://github.com/user-attachments/assets/7a117106-597e-46a2-85b0-7370271b43ba" />
<img width="1728" height="1117" alt="7" src="https://github.com/user-attachments/assets/f8484edb-12c4-4f17-b0c4-b08c01dc4355" />
