# vendor_xiaomi_miuicamera
Miui Camera Support for **Adi's Device Tree** (Davinci)

Leica Camera 5.0 for Mi 9T/Redmi K20 (davinci) AOSP

### **Cloning :**

Clone this repo in vendor/xiaomi/miuicamera in your working directory by :


```
git clone https://github.com/hursitwww/vendor_xiaomi_miuicamera.git vendor/xiaomi/miuicamera
```

**Make these changes in sm6150-common**

**sm6150.mk**

```# MiuiCamera
$(call inherit-product, vendor/xiaomi/miuicamera/config.mk)
```
