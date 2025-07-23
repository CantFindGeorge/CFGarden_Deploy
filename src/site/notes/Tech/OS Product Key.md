---
{"dg-publish":true,"permalink":"/tech/os-product-key/","tags":["Tech"],"updated":"2025-07-22T23:03:17.075-04:00"}
---

# What is this?
It's important that you double check if your OS has a product key. Depending on what operating system a license can cost $100 or more. So it's important to check if your OS has a product key and you note it down or activate it accordingly.

---
# Windows 
## Modern Versions
On windows 10 or 11 your product key will be automatically synced if you connected a Microsoft account. 
## Older Versions
On windows 8.1 or older you'll need a product key to activate your license. Open up the console and run the following command line and it will provide the product key so you can note it down.

| Windows<br>Version              | Command                                                         |
| ------------------------------- | --------------------------------------------------------------- |
| ME, XP, Vista, <br>7, and 8/8.1 | `wmic path softwarelicensingservice get OA3xOriginalProductKey` |
| Server                          | `wmic path softwareLicensingService get OA3xOriginalProductKey` |
| 98                              | `C:\>find /i "ProductKey" C:\windows\system.dat`                |
| 95                              | Use `111–1111111` or `000–0000007` as a product ket             |

---
# No Keys Required

- Chrome OS Flex
- Linux based OS
- Mac - You just need to sign into your apple account

