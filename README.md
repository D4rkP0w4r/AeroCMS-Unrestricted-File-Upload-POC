# AeroCMS-Unrestricted-File-Upload-POC
## Step to Reproduct
* Login to admin panel -> `Posts` -> `Add Posts` -> `Post Image` -> upload malicious file `shell.php` -> access `/images/shell.php` on url -> `shell.php page`
### Exploit
![image](https://user-images.githubusercontent.com/79050415/157000088-368ebaa1-b275-4647-bbc5-c67b7a599467.png)
* When upload success access `/images/shell.php`
![image](https://user-images.githubusercontent.com/79050415/157001048-4deb194c-2a9c-437d-8eb6-5d6a1b452cf6.png)
* Niceeee web shell active
![image](https://user-images.githubusercontent.com/79050415/157001142-334f5f43-cea9-4711-a56a-1b4494f118d3.png)

