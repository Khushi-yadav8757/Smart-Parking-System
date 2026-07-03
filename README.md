# 🅿️ Smart Parking System using Computer Vision

A Computer Vision based Smart Parking System that detects free and occupied parking spaces in real-time from video feeds using Python and OpenCV.

This project helps in monitoring parking availability automatically and can be used in smart cities, malls, offices, and parking management systems.

---

## 📌 Features 

- Detects free and occupied parking slots in real time  
- Uses image processing instead of physical sensors  
- Shows live parking availability count  
- Highlights:
  - 🟩 Green → Free parking space  
  - 🟥 Red → Occupied parking space  
- Works on video feeds (CCTV or recorded footage)

---

## 🛠️ Technologies Used

- Python  
- OpenCV  
- NumPy  
- cvzone  
- Pickle  

---

## 🧠 How It Works

1. The parking area image is loaded.
2. Parking slot positions are marked manually using ParkingSpacePicker.py.
3. The video is processed frame by frame.
4. Each parking slot is analyzed using pixel intensity.
5. If pixel count is low → Slot is free.
6. If pixel count is high → Slot is occupied.
7. The system displays the result in real time.

---

## 📂 Project Structure

```text
Smart-Parking-System
│
├── main.py
├── ParkingSpacePicker.py
├── carPark.mp4
├── carParkImg.png
├── CarParkPos
└── README.md
```


---

## ▶️ How to Run the Project

### 1️⃣ Install Required Libraries


---

### 2️⃣ Mark Parking Spaces


- Left Click → Add parking slot  
- Right Click → Remove parking slot  

After marking all slots, close the window.

---

### 3️⃣ Run Parking Detection


You will see:
- Red boxes for occupied spaces  
- Green boxes for free spaces  
- Total free parking slots displayed on screen  

---

## 📊 Sample Output

Example:

---

## 🚀 Future Enhancements

- AI based car detection (YOLO)
- Web dashboard
- Mobile app integration
- Live CCTV camera support
- Parking payment system

---

## 👩‍💻 Developer

**Khushi Yadav**  
GitHub: https://github.com/Khushi-yadav8757

If you like this project, feel free to ⭐ star the repository 😊

