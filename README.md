### <p align="center">💥 EMAIL GENERATOR 💥</p>
-----

<p align="center">
<img src="https://github.com/GarudaID/email-gen/blob/main/pict.PNG", width="500", height="500">
</p><br>
Install Module : pip install faker

-----

### <p align="center">Example Code</p>

```py
try:
        int(number_of_mails)
    except:
        raise ValueError('Enter an integer!')

    for i in range(number_of_emails):
        name = fake.name()
        name = name.replace(" ","")
        name = name.lower()

        num = random.randint(0,1000)
        num = str(num)

        domain = random.choice(domains)

        e_name = name
        e_name += num

        full_email = e_name+domain

        url = "https://mailsac.com/inbox/"

        print(url+e_name+domain)
        print(full_email)
        print('======================')
```

-----

### <p align="center">⭐ Features ⭐</p>

<br><br>
<strong>+ Very fast execution (under 0.002ms!)</strong>
<br>
<a href="https://github.com/GarudaID/email-gen/releases/tag/Release">Go Click here for download</a>

-----

### <p align="center">📌 Disclaimer 📌</p>

<br><br>
* ***Please use this program only for educational purposes.***
* ***It is not meant to be used in any malicious way, and I decline any responsibility for what you do with it.***
<br><br>

-----
