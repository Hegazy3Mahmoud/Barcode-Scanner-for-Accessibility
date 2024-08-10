# QR Code and Barcode Scanner for Accessibility

## Overview

This project is a graduation project designed to help blind people navigate markets and other shopping environments by providing information about products through QR codes and barcodes. The tool scans QR codes and barcodes to read out product information, making it easier for visually impaired individuals to make informed decisions while shopping.

## Features

- **Real-Time QR Code and Barcode Scanning**: Captures and processes QR codes and barcodes using a webcam.
- **Product Information**: Fetches and reads out information about products, including name, description, price, and currency.
- **Multilingual Support**: The text-to-speech engine supports multiple languages, making it adaptable to various languages and regions.
- **API Integration and Local Data Handling**: Can fetch product details from an online API or process data from a local JSON file.

## Purpose

Blind and visually impaired individuals often rely on navigational tools to move around, but they face challenges when shopping in markets where product information is not readily accessible. This project aims to address this gap by providing a solution that helps blind individuals identify and understand products they encounter in stores.

Through the use of QR codes and barcodes, this tool enables users to receive detailed information about products, which is spoken out loud through a text-to-speech system. This can significantly enhance the shopping experience for blind people, offering them greater independence and confidence while shopping.

## How It Works

1. **Scanning**: The system captures real-time video from a webcam and processes it to detect QR codes or barcodes.
2. **Decoding**: The QR code or barcode data is decoded to retrieve the product information.
3. **Fetching Data**: Depending on the mode of operation, the system either queries an online API or looks up product information from a local data file.
4. **Text-to-Speech**: The retrieved product details are spoken out loud to the user.

## Setup

1. **Install Required Libraries**:
   ```bash
   pip install opencv-python pyzbar pyttsx3 pandas requests
