<p align="center">
    <a href="https://smartproxy.com/"><img src="https://smartproxy.com/wp-content/themes/smartproxy/images/smartproxy-logo.svg" alt="Smartproxy logo" width="200" height="50"></a>
  </a>
</p>

<p align="center">
    <a href="https://github.com/Smartproxy/Smartproxy"> :house: Main Repository :house: </a>
</p>

### Disclaimer

The following example is a simple script showing how to utilize Smartproxy with Scrapy.
We suggest to reseach [Scrapy](https://docs.scrapy.org/en/latest/) documentation in order to continue development with this tool.

### Prerequisites

To get started with Scrapy you will first need to install it using methods provided in their documentation. [Check here for more information](https://docs.scrapy.org/en/latest/intro/install.html)

### Installation

Once you get Scrapy up and running if you have not yet, make sure that you create your project folder. Open the Terminal/Command prompt window and enter the command bellow:

```
scrapy startproject yourprojectname
```
<img src="https://content.screencast.com/users/JohanSP/folders/Jing/media/f974b1de-dc9c-4d53-9d43-9215f8742dc9/startproject.png">

When project directory is setup, you can now download our test spider code: 

1. Make sure to open the exact location in your project folder using `cd .\yourprojectname\yourprojectname\spiders\`
2. To download our example script, run command `curl https://raw.githubusercontent.com/Smartproxy/Scrapy/master/smartproxy_spider.py > smartproxy_spider.py`
3. Run the script using `scrapy crawl smartproxy` command.
<img src="https://content.screencast.com/users/JohanSP/folders/Jing/media/79c69577-0034-40e8-b1e5-161cad99031a/2019-03-08_1627.png">

Note that the code may not run if the `smartproxy_spider.py` file is in the wrong directory.

### How to check if it works?

As mentioned this script only sends a basic request to return a value from the target website.

If you done all the steps correctly, you should see the result as `{'price': '£51.77'}` along with other actions performed by Scrapy in the Terminal window.

<img src="https://snipboard.io/0dr1Ch.jpg">

## Need help?
Email - sales@smartproxy.com
<br><a href="https://smartproxy.com">Live chat 24/7</a>


