<div align="center">
    <a href="https://thinknxg">
        <img src="https://thinknxg.com/wp-content/uploads/2023/12/favicon.svg1-01.png" height="128">
    </a>
    <h2>thinkNXG whitelabel</h2>
    

</div>

# thinknxg ERP Whitelabel

This app has the following features:

- Change App logo
- Change Favicon
- Change Splash Image
- Hide Help Menu
- Hide "powered by" text from the website
- Remove welcome page
- Update welcome blog post
- Adjust App logo size from Whitelabel setting page
- Update onboard steps to remove video and documentation link (Version 13)
- Manage Navbar Background color from Whitelabel setting
- Manage Custom Navbar Title and CSS for title from Whitelabel setting
- Change Login Page Title from Whitelabel Setting Page 



Whitelabel Setting Page
![image](https://user-images.githubusercontent.com/34086262/115605632-5e28ed00-a300-11eb-986d-5114ef128de3.png)

Custom Navbar Title
![image](https://user-images.githubusercontent.com/34086262/115721516-bc56de00-a39b-11eb-94b3-787b0481fb60.png)

Below are important settings in the Whitelabel setting page:

1. Ignore Onboard Whitelabel:
   - If this setting value is true, then this app will not whitelabel onboarding steps and onboarding modules.

2. Show help menu:
   - By default, this app hides the help menu. This setting shows the help menu if the value of this setting is true.

3. Disable New Update Popup:
   - If this setting value is true, then it will disable the new updates popup.


## Installation Steps:

1. Clone the repository:
   bench get-app https://github.com/thinknxg/thinknxg-whitelabel

3. Install the app for a specific site:
   bench --site sitename install-app whitelabel

3. Migrate the database:
   bench  --site site_name migrate

4. Restart the bench:
   bench restart

5. Clear the cache:
   bench clear-cache


## License
Distributed under [GNU AFFERO GENERAL PUBLIC LICENSE](license.txt)


