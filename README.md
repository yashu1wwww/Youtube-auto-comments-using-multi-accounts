# Youtube-auto-comments-using-multi-accounts
Youtube auto comments using multi accounts using selenium with python

👉NOTE:-Without adding proxies some comments will remove by youtube because of same ip location so see the screenshot and modify to that to in comment.py script👍 

#Replace Email and Pass in 14 & 15 line and also in 522 and 523 line 

change url in url.txt file which url you required and change the cmt text if you needed to your required cmts in 11 and 519 line...

After download the folder extract it and open cmd and enter Python If You Find Python Version

Then enter pip install undetected_chromedriver in cmd and hit enter button (internet connection will be in on)

and enter pip install random in cmd and hit enter button

and Pip install Proxy in cmd and hit enter button

After download the chromedriver(https://chromedriver.chromium.org/downloads extract these to downloaded folder)and with matches your chrome version of your pc and

enter comment.py in cmd on that particular folder or double click on comment.py.... 

👉Python Install Setup=https://youtu.be/4bUOrMj88Pc

👉Note:-

👉if your selenium version is in latest version then 
the code never run 

👉open cmd and enter pip uninstall selenium

And enter 

pip install selenium==4.2.1
or
pip install selenium==4.2.0

and hit enter 

and 

python -c "import selenium; print(selenium.__version__)"
<to check the current version of selenium>


𝙏𝙝𝙞𝙨 𝙞𝙣𝙛𝙤𝙧𝙢𝙖𝙩𝙞𝙤𝙣 𝙞𝙨 𝙤𝙣𝙡𝙮 𝙛𝙤𝙧 𝙚𝙙𝙪𝙘𝙖𝙩𝙞𝙤𝙣al 𝙥𝙪𝙧𝙥𝙤𝙨𝙚 𝙖𝙣𝙙 𝙬𝙚 𝙖𝙧𝙚 𝙣𝙤𝙩 𝙧𝙚𝙨𝙥𝙤𝙣𝙨𝙞𝙗𝙡𝙚 𝙛𝙤𝙧 𝙖𝙣𝙮 𝙠𝙞𝙣𝙙 𝙤𝙛 𝙞𝙡𝙡𝙚𝙜𝙖𝙡 𝙖𝙘𝙩𝙞𝙫𝙞𝙩𝙮 𝙙𝙤𝙣𝙚 𝙗𝙮 𝙩𝙝𝙞𝙨 𝙩𝙤𝙤𝙡.

if you cmt on your brand acc also means below is the code make separate py file for each brand acc below is the code....

wait.until(EC.visibility_of_element_located((By.NAME,'identifier'))).send_keys(email)
#time.sleep(2)
wait.until(EC.visibility_of_element_located((By.NAME,'Passwd'))).send_keys(password)
time.sleep(11) #if click on brand acc 2 changes to 11 or 12,13

if click on 1st brand account

driver.find_element_by_xpath('/html/body/ytd-app/ytd-popup-container/tp-yt-paper-dialog/ytd-channel-switcher-renderer/div[2]/div/ytd-account-item-section-renderer/div[2]/ytd-account-item-renderer[1]/tp-yt-paper-icon-item/tp-yt-paper-item-body/yt-formatted-string[1]').click()

if click on 2nd brand account

driver.find_element_by_xpath('/html/body/ytd-app/ytd-popup-container/tp-yt-paper-dialog/ytd-channel-switcher-renderer/div[2]/div/ytd-account-item-section-renderer/div[2]/ytd-account-item-renderer[2]/tp-yt-paper-icon-item/tp-yt-paper-item-body/yt-formatted-string[1]').click()

if click on 3rd brand account

driver.find_element_by_xpath('/html/body/ytd-app/ytd-popup-container/tp-yt-paper-dialog/ytd-channel-switcher-renderer/div[2]/div/ytd-account-item-section-renderer/div[2]/ytd-account-item-renderer[3]/tp-yt-paper-icon-item/tp-yt-paper-item-body/yt-formatted-string[1]').click()

if click on 4th brand account

driver.find_element_by_xpath('/html/body/ytd-app/ytd-popup-container/tp-yt-paper-dialog/ytd-channel-switcher-renderer/div[2]/div/ytd-account-item-section-renderer/div[2]/ytd-account-item-renderer[4]/tp-yt-paper-icon-item/tp-yt-paper-item-body/yt-formatted-string[1]').click()

if click on 5th brand account

driver.find_element_by_xpath('/html/body/ytd-app/ytd-popup-container/tp-yt-paper-dialog/ytd-channel-switcher-renderer/div[2]/div/ytd-account-item-section-renderer/div[2]/ytd-account-item-renderer[5]/tp-yt-paper-icon-item/tp-yt-paper-item-body/yt-formatted-string[1]').click()

if click on 6th brand account

driver.find_element_by_xpath('/html/body/ytd-app/ytd-popup-container/tp-yt-paper-dialog/ytd-channel-switcher-renderer/div[2]/div/ytd-account-item-section-renderer/div[2]/ytd-account-item-renderer[6]/tp-yt-paper-icon-item/tp-yt-paper-item-body/yt-formatted-string[1]').click()

if click on 7th brand account

driver.find_element_by_xpath('/html/body/ytd-app/ytd-popup-container/tp-yt-paper-dialog/ytd-channel-switcher-renderer/div[2]/div/ytd-account-item-section-renderer/div[2]/ytd-account-item-renderer[7]/tp-yt-paper-icon-item/tp-yt-paper-item-body/yt-formatted-string[1]').click()

if click on 8th brand account

driver.find_element_by_xpath('/html/body/ytd-app/ytd-popup-container/tp-yt-paper-dialog/ytd-channel-switcher-renderer/div[2]/div/ytd-account-item-section-renderer/div[2]/ytd-account-item-renderer[8]/tp-yt-paper-icon-item/tp-yt-paper-item-body/yt-formatted-string[1]').click()

time.sleep(3)
