# Magento Mobile Detect
Simple Magento mobile detect module for 1.9.2.x versions

Mobile_Detect is a lightweight PHP class for detecting mobile devices (including tablets). It uses the User-Agent string combined with specific HTTP headers to detect the mobile environment. http://mobiledetect.net 

## Usage

In template.phtml:

```
// Detect
<?php
$helper = Mage::helper('wpositive_mobiledetect/data');

if($helper->isMobile()) {
  echo "is_mobile";
}
?>
```


