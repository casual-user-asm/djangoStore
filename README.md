<h1>Clothes-Store</h1>

Clothes-Store is an online shopping platform that offers a seamless experience for users to explore, purchase, and manage their clothing orders.

## Configure Stripe Settings

Add your Stripe API keys to your Django settings (settings.py):
  - STRIPE_PUBLIC_KEY = 'your_public_key'
  - STRIPE_SECRET_KEY = 'your_secret_key'
  - STRIPE_WEBHOOK_SECRET = 'your_webhook_secret'

## If you need additional features or customization, refer to the Stripe API(https://docs.stripe.com/api) documentation for more details.

## Installation

First, clone this repository:

<!-- start:code block -->
# Clone this repository
git clone https://github.com/casual-user-asm/djangoStore.git

# Go to project directory
cd djangoStore

# Install dependencies
pip install -r requirements.txt

# Run the bot
python manage.py runserver

<!-- end:code block -->
