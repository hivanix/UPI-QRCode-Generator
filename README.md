
# 🚀 Hivanix - UPI QR Generator

A modern, beautiful, and feature-rich UPI QR code generator with glass-morphism design and multiple payment options.

## ✨ Features

### 🎨 **Design & UI**
- **Glass-morphism Design**: Modern frosted glass effect with backdrop blur
- **Light Green Theme**: Soft, professional color palette
- **Animated Background**: Floating bubbles and gradient orbs
- **Responsive Layout**: Works perfectly on all devices
- **Smooth Animations**: Micro-interactions and transitions throughout

### 💳 **Payment Options**
1. **UPI ID**: Smart autocomplete with 30+ providers
2. **Phone Number**: 10-digit validation with @paytm
3. **Bank Account**: Account number + IFSC code
4. **Aadhaar**: 12-digit validation with @upi

### 🔧 **Core Features**
- **Smart Autocomplete**: Shows UPI providers when typing `@`
- **Real-time Validation**: Instant feedback for all inputs
- **QR Code Generation**: Creates scannable UPI QR codes
- **Download Function**: Save QR codes as PNG images
- **Phone Integration**: Open directly in UPI apps
- **Particle Effects**: Beautiful animations on generation

## 📁 Project Structure

```
upi-qr-generator/
├── index.html              # Main application file
├── README.md               # This documentation
```

## 🚀 Getting Started

### **Installation**
1. Clone or download the project files
2. Open `index.html` in your web browser
3. The application is ready to use!

## 📖 Usage Guide

### **Generate UPI QR Code**

1. **Select Payment Type**:
   - **UPI ID**: Enter your UPI ID (e.g., `username@paytm`)
   - **Phone**: Enter 10-digit mobile number
   - **Bank**: Enter account number + IFSC code
   - **Aadhaar**: Enter 12-digit Aadhaar number

2. **Fill Required Fields**:
   - Merchant/Payee Name
   - Payment details (based on selected type)
   - Transaction Amount (optional)
   - Description/Notes (optional)

3. **Generate QR Code**:
   - Click "Generate QR Code" button
   - QR code appears with animation
   - Download or share options available

### **Autocomplete Feature**
- Type `@` in UPI ID field
- See dropdown with popular providers:
  - Paytm, PhonePe, Google Pay
  - Amazon Pay, BHIM, WhatsApp Pay
  - And 25+ more providers

### **QR Code Actions**
- **Download**: Save as PNG image
- **Open on Phone**: Launch UPI app directly
- **Scan**: Use any QR scanner app

## 🔧 Configuration

### **UPI Providers Supported**
The application includes 30+ UPI providers:
- Paytm, PhonePe, Google Pay, Amazon Pay
- BHIM, WhatsApp Pay, Freecharge, Mobikwik
- Airtel Money, JioMoney, SBI Pay, HDFC Pay
- ICICI Pay, Axis Pay, PNB, BOI
- Canara Bank, Bank of Baroda, Union Bank
- Kotak, IndusInd, RBL Bank, Yes Bank
- IDFC Bank, Federal Bank, SLC, Jupiter, Fi

### **UPI URL Format**
Generated QR codes use standard UPI URL format:
```
upi://pay?pa={payment_address}&pn={merchant_name}&am={amount}&mc=0000&mode=02&purpose=00&tn={description}
```

**Made with ❤️ by Hivanix Team**
