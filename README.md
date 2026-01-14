# PLUTO PLAY

- LIVE -> https://plutoplay.netlify.app/

A YouTube-inspired video streaming web application built with React and Redux, focusing on performance optimization, scalable state management, and smooth user experience.

## 🎥 Video Streaming Web Application (React + Redux)

This project replicates core features of modern video streaming platforms while emphasizing efficient state handling and UI performance.

## 🔹 Key Features
- Optimized Redux store to efficiently manage application state
- API caching for visited videos to reduce redundant network requests
- Live chat system with controlled state updates to prevent UI freezes
- Automatic cleanup by removing older chat messages beyond a fixed limit (e.g., last 15 messages)
- Responsive UI inspired by modern video streaming platforms
- Optimized re-renders and asynchronous data handling
- Debouncing:

typing slow = 200ms typing fast = 30ms

Perfomance:

iphone pro max = 14 letter * 1000 = 140000
with debouncing= 3 API calls * 1000 = 3000
Debouncing with 200ms

if difference between 2 key strokes is <200ms - DECLINE API call
200ms make an API call

Cache: time complexity tro search in array = O(n) time complexity tro search in Object = O(1)

[i, ip, iph, iphone]

{ i: ip: iph: iphone: }

## 🔹 Tech Stack
- **Frontend:** React, JavaScript (ES6+), HTML, CSS, Tailwind CSS
- **State Management:** Redux
- **APIs:** Public video data APIs
- **Tools:** Git, GitHub
