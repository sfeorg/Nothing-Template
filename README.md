
<p align="center">
  <a href="https://github.com/sfeorg/Nothing-Template" target="_blank" rel="noopener noreferrer">
    <img src="https://github.com/sfeorg/Nothing-Template/blob/main/pc-shot.jpg" title="Nothing-Template"/>
  </a>
   <a href="https://github.com/sfeorg/Nothing-Template" target="_blank" rel="noopener noreferrer">
    <img src="https://github.com/sfeorg/Nothing-Template/blob/main/android.png" title="Nothing-Template"/>
  </a>
</p>
<h1 align="center">Subscription Template for <a href="https://github.com/rebeccapanel/Rebecca">rebecca Panel</a></h1>

Faster and easier than ever :)
# Installation Steps
1. Download the template file:
```sh
sudo wget -N -P /var/lib/rebecca/templates/subscription/ https://github.com/sfeorg/Nothing-Template/blob/main/index.html
```

2.	Run the following commands in your server terminal:

```sh
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/rebecca/templates/"' | sudo tee -a /opt/rebecca/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/rebecca/.env
```

Alternatively, uncomment the following values in the `.env` file located in /opt/marzban by removing the # symbol:

```sh
CUSTOM_TEMPLATES_DIRECTORY="/var/lib/rebecca/templates/"
SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"
```
