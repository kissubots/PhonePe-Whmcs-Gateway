# 📱 Phonepe WHMCS Module Master

## 🌟 Introduction

Welcome to the **Phonepe WHMCS Module**! This powerful integration kit allows you to seamlessly incorporate the Phonepe payment gateway into your WHMCS PHP E-Commerce application. With this module, you can enhance your payment processing capabilities and provide your customers with a smooth and secure checkout experience.

![Phonepe Logo](https://example.com/path/to/phonepe-logo.png) <!-- Replace with actual image URL -->

---

## 🚀 Installation

Getting started with the Phonepe WHMCS Module is easy! Follow these simple steps to install the module:

1. **Copy the Gateway File**  
   Place the `phonepe.php` file into your WHMCS installation's `/modules/gateways/` directory.

   ![Copy Gateway File](https://example.com/path/to/copy-gateway-file.png) <!-- Replace with actual image URL -->

2. **Copy the Callback File**  
   Move the `phonepe.php` file from the `callback` folder into your WHMCS installation's `/modules/gateways/callback/` directory.

   ![Copy Callback File](https://example.com/path/to/copy-callback-file.png) <!-- Replace with actual image URL -->

3. **Copy the SDK Folder**  
   Transfer the entire `phonepe-sdk` folder into your WHMCS installation's `/modules/gateways/` directory.

   ![Copy SDK Folder](https://example.com/path/to/copy-sdk-folder.png) <!-- Replace with actual image URL -->

---

## ⚙️ Configuration

After installation, you need to configure the module to connect with the Phonepe payment gateway. Follow these steps in the **Configuration Settings** of the WHMCS Admin Panel:

1. **Merchant ID**: Enter your unique Merchant ID.
2. **Salt Key**: Provide the Salt Key for secure transactions.
3. **Salt Index**: Specify the Salt Index for your account.
4. **Production URL**: Input the appropriate Production URL.

![Configuration Settings](https://example.com/path/to/configuration-settings.png) <!-- Replace with actual image URL -->

---

## 🌐 Phonepe PG URL Details

### 🛠️ Staging Environment
- **Production URL**:  
  `https://api-preprod.phonepe.com/apis/pg-sandbox/pg/v1`
  
- **Salt Key**:  
  `099eb0cd-02cf-4e2a-8aca-3e6c6aff0399`
  
- **Salt Index**:  
  `1`
  
- **Merchant ID**:  
  `PGTESTPAYUAT`

### 🚀 Production Environment
- **Production URL**:  
  `https://api.phonepe.com/apis/hermes/pg/v1`

---

## 🎉 Conclusion

With the Phonepe WHMCS Module, you can elevate your e-commerce platform by providing a reliable and efficient payment solution. Follow the installation and configuration steps to get started, and enjoy the benefits of seamless transactions with Phonepe!

For any questions or support, feel free to reach out to our support team. Happy selling! 🎊

![Happy Selling](https://example.com/path/to/happy-selling.png) <!-- Replace with actual image URL -->
