import requests
import os
import random

print('''
⠀⠀⠀⠀⠀⠀⠀⣀⣀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⢀⣠⣶⣿⣿⣿⣄⣀⣀⣀⣀⣀⣀⣠⣿⣿⣿⣶⣄⡀⠀⠀⠀
⠀⠀⢀⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⡀⠀⠀
⠀⠀⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⠀⠀
⠀⢰⣿⣿⣿⣿⣿⡿⠋⠉⠻⣿⣿⣿⣿⠟⠉⠙⢿⣿⣿⣿⣿⣿⡆⠀
⠀⣿⣿⣿⣿⣿⣿⡇⠀⠀⠀⣿⣿⣿⣿⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⠀
⢀⣿⣿⣿⣿⣿⣿⣿⣄⣀⣴⣿⣿⣿⣿⣦⣀⣠⣾⣿⣿⣿⣿⣿⣿⡀
⢸⣿⣿⣿⣿⡿⠛⠛⠻⠿⢿⣿⣿⣿⣿⡿⠿⠛⠛⠛⢿⣿⣿⣿⣿⡇
⠈⢿⣿⣿⣿⣧⣄⣀⡀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣀⣠⣼⣿⣿⣿⡿⠁
⠀⠀⠉⠛⠿⠿⣿⣿⠋⠀⠀⠀⠀⠀⠀⠀⠀⠙⣿⣿⠿⠿⠛⠉⠀⠀
''')

token = input("#8768: ")
id = input('moke_1 : ')
os.system('clear')
print('''

 ⚜️ • 𝐇𝐎𝐖 𝐋𝐎𝐍𝐆 𝐈𝐒 𝐓𝐇𝐄 𝐔𝐒𝐄𝐑 • ⚜️
   
    [1] ➠ three 👨🏻‍💻
    [2] ➠ four  🏹
    [3] ➠ Five  ✨

''')
Tool = input('[+] Choose : ')
if Tool == "1":
    os.system('clear')
    while True:
            usr= 'qwertyuiopasdfghjklzxcvbnm1234567890'
            username = str(''.join((random.choice(usr) for i in range(3))))
            cookies = {
    '__dcfduid': '9da2d7500f0611ef8b94915b10020fc2',
    '__sdcfduid': '9da2d7510f0611ef8b94915b10020fc2bc1000bf2f2ed1e1f932f9f979e7f9b2a9a4b1dfc15db351e6538cf2f21e0380',
    '__cfruid': '57b71d2296ecac171040915a91e003e88acc6fca-1715370656',
    '_cfuvid': 'RKf5c0NWZjes8xlY65IkEF_yVuLLi5yAx60dkUKUjI0-1715370656073-0.0.1.1-604800000',
    'cf_clearance': 'gmN2Cxv3_D8yKND9zz_mabgLKR6TOiLU4Vk46zB1oH8-1715370659-1.0.1.1-iBCoTXHXuUkPNKe6nP5pdyk6eO4NLdsfuE8ea_GJC2pVyfCLi41AdcQOY5qUhV5lTs5D4bZcRLGk5CqVbT1jnA',
}

            headers = {
    'authority': 'discord.com',
    'accept': '*/*',
    'accept-language': 'ar-IQ,ar;q=0.9,en-US;q=0.8,en;q=0.7',
    'content-type': 'application/json',
    # 'cookie': '__dcfduid=9da2d7500f0611ef8b94915b10020fc2; __sdcfduid=9da2d7510f0611ef8b94915b10020fc2bc1000bf2f2ed1e1f932f9f979e7f9b2a9a4b1dfc15db351e6538cf2f21e0380; __cfruid=57b71d2296ecac171040915a91e003e88acc6fca-1715370656; _cfuvid=RKf5c0NWZjes8xlY65IkEF_yVuLLi5yAx60dkUKUjI0-1715370656073-0.0.1.1-604800000; cf_clearance=gmN2Cxv3_D8yKND9zz_mabgLKR6TOiLU4Vk46zB1oH8-1715370659-1.0.1.1-iBCoTXHXuUkPNKe6nP5pdyk6eO4NLdsfuE8ea_GJC2pVyfCLi41AdcQOY5qUhV5lTs5D4bZcRLGk5CqVbT1jnA',
    'origin': 'https://discord.com',
    'referer': 'https://discord.com/register',
    'sec-ch-ua': '"Not-A.Brand";v="99", "Chromium";v="124"',
    'sec-ch-ua-mobile': '?1',
    'sec-ch-ua-platform': '"Android"',
    'sec-fetch-dest': 'empty',
    'sec-fetch-mode': 'cors',
    'sec-fetch-site': 'same-origin',
    'user-agent': 'Mozilla/5.0 (Linux; Android 10; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/124.0.0.0 Mobile Safari/537.36',
    'x-debug-options': 'bugReporterEnabled',
    'x-discord-locale': 'en-US',
    'x-discord-timezone': 'Asia/Baghdad',
    'x-fingerprint': '1238579058007347222.yhvxzFxABpjEHsan6cPullFm3xE',
    'x-super-properties': 'eyJvcyI6IkFuZHJvaWQiLCJicm93c2VyIjoiQW5kcm9pZCBDaHJvbWUiLCJkZXZpY2UiOiJBbmRyb2lkIiwic3lzdGVtX2xvY2FsZSI6ImFyLUlRIiwiYnJvd3Nlcl91c2VyX2FnZW50IjoiTW96aWxsYS81LjAgKExpbnV4OyBBbmRyb2lkIDEwOyBLKSBBcHBsZVdlYktpdC81MzcuMzYgKEtIVE1MLCBsaWtlIEdlY2tvKSBDaHJvbWUvMTI0LjAuMC4wIE1vYmlsZSBTYWZhcmkvNTM3LjM2IiwiYnJvd3Nlcl92ZXJzaW9uIjoiMTI0LjAuMC4wIiwib3NfdmVyc2lvbiI6IjEwIiwicmVmZXJyZXIiOiIiLCJyZWZlcnJpbmdfZG9tYWluIjoiIiwicmVmZXJyZXJfY3VycmVudCI6IiIsInJlZmVycmluZ19kb21haW5fY3VycmVudCI6IiIsInJlbGVhc2VfY2hhbm5lbCI6InN0YWJsZSIsImNsaWVudF9idWlsZF9udW1iZXIiOjI5MTk2MywiY2xpZW50X2V2ZW50X3NvdXJjZSI6bnVsbCwiZGVzaWduX2lkIjowfQ==',
}

            json_data = {
    'fingerprint': '1238579058007347222.yhvxzFxABpjEHsan6cPullFm3xE',
    'email': 'ALi@gmail.com',
    'username': username,
    'global_name': 'ALI',
    'password': 'lol',
    'invite': None,
    'consent': True,
    'date_of_birth': '2000-06-07',
    'gift_code_sku_id': None,
    'promotional_email_opt_in': True,
}

            response = requests.post('https://discord.com/api/v9/auth/register', cookies=cookies, headers=headers, json=json_data)
            if "USERNAME_ALREADY_TAKEN" and "Username is unavailable. Try adding numbers, letters, underscores _ , or periods." in response.text:
                  print(f'[!] ❌ : {username} ')
            elif "captcha_sitekey" and "captcha-required" or "captcha_key" or "captcha_service" or "hcaptcha" in response:
                  print(f"[!] ✅ : {username}")
                  https://discord.com
