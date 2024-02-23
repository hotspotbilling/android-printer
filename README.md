# Android Thermal Printer Client

is a client to print phpnuxbill voucher or invoice to bluetooth Thermal Printer

## Download

Download from [Release Page](https://github.com/hotspotbilling/android-printer/releases)

## Android API

Call it via Intent or Deeplink
```
nux://print?text=Encoded%20Text
```

```java
startActivity(new Intent(Intent.ACTION_VIEW, Uri.parse("nux://print?text=Encoded%20Text")));
```

```html
<a href="nux://print?text=Encoded%20Text">Print</a>
```

## Deploy for yours only

i can build for your Business for only $50 talk to me [ibnux](https://t.me/ibnux)
