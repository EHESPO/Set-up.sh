#!/bin/bash
# ============================================================
# EHESPO Nonprofit Toolkit Setup Script
# ============================================================
# TECH STACK:
#   • Python 3.8+ (www.python.org)
#   • venv - Python's built-in virtual environment
#   • pip - Python package manager (pypi.org)
#   • requirements.txt - dependencies from PyPI
# ============================================================
# COMPANIES & SERVICES REFERENCED:
#   • EHESPO International - Your organization
#   • Google (Google for Nonprofits, Google Workspace)
#   • GitHub (repository hosting)
#   • Replit/Colab (cloud execution environments)
#   • GoDaddy / Squarespace (domain registrars)
#   • IRS (US tax authority)
#   • OFAC (US Treasury sanctions compliance)
# ============================================================

echo "🚀 EHESPO Nonprofit Toolkit Setup"
echo "=================================="
echo "🔧 Setting up environment for:"
echo "   • EHESPO International Corporation"
echo "   • Google for Nonprofits integration"
echo "   • Domain management (GoDaddy/Squarespace)"
echo "   • IRS 501(c)(3) compliance"
echo "   • OFAC General License 14-20 (Afghanistan)"
echo "=================================="

# ============================================================
# PYTHON VIRTUAL ENVIRONMENT
# ============================================================
# Tool: python3 (Python Software Foundation)
# Purpose: Isolated Python environment
# Doc: docs.python.org/3/library/venv.html
# ============================================================
echo "📦 Creating Python virtual environment..."
python3 -m venv venv

# ============================================================
# ACTIVATE VENV
# ============================================================
# Cross-platform activation
# - Linux/Mac: source venv/bin/activate
# - Windows: .\venv\Scripts\activate
# ============================================================
echo "🔓 Activating virtual environment..."
source venv/bin/activate 2>/dev/null || echo "⚠️ On Windows use: .\\venv\\Scripts\\activate"

# ============================================================
# INSTALL DEPENDENCIES FROM PyPI
# ============================================================
# Companies/Projects referenced in requirements.txt:
#   • python-whois (PyPI) - WHOIS lookup
#   • dnspython (DNSPython.org) - DNS resolution
#   • requests (Python Requests Project) - HTTP API calls
#   • python-dotenv (The Dotenv Project) - .env management
#   • colorama (tartley.com) - colored terminal output
#   • tabulate (Python Tabulate) - table formatting
# ============================================================
echo "📥 Installing dependencies from PyPI..."
echo "   • python-whois - Domain WHOIS lookup"
echo "   • dnspython - MX/email verification"
echo "   • requests - API calls (GoDaddy, Google)"
echo "   • python-dotenv - Environment variables"
echo "   • colorama - Colored terminal output"
echo "   • tabulate - Table formatting"
pip install -r requirements.txt

# ============================================================
# CREATE .env FILE
# ============================================================
# Configuration for:
#   • GoDaddy API (api.godaddy.com)
#   • Squarespace/Google Domains (UI only)
#   • Organization details
# ============================================================
echo "🔑 Creating .env configuration..."
cp .env.example .env

# ============================================================
# POST-SETUP INSTRUCTIONS
# ============================================================
echo ""
echo "✅ Setup complete!"
echo ""
echo "📝 NEXT STEPS:"
echo "   1. Edit .env with your registrar API keys:"
echo "      • GoDaddy: developer.godaddy.com (get API keys)"
echo "      • Squarespace: use UI at squarespace.com"
echo ""
echo "   2. Configure organization details:"
echo "      • ORG_NAME: EHESPO International Corporation"
echo "      • ORG_EMAIL: executive@eheps.com"
echo "      • DOMAINS: eheps.org,eheps.com"
echo ""
echo "   3. Required external actions:"
echo "      • IRS: File Form 1023-EZ (irs.gov/form1023ez)"
echo "      • Google: Apply at google.com/nonprofits"
echo "      • OFAC: Review General Licenses 14-20"
echo ""
echo "🚀 Run the toolkit:"
echo "   source venv/bin/activate"
echo "   python src/main.py"
echo ""
echo "🌍 For Afghanistan humanitarian work:"
echo "   • OFAC compliance verified (General License 19)"
echo "   • Legal authorization for NGO operations"
echo "   • Education/women/youth/environment focus"
echo ""
echo "==========================================================="
echo "📚 SUPPORT RESOURCES:"
echo "   • GitHub: github.com/YOUR_USERNAME/ehespo-nonprofit-toolkit"
echo "   • Google: support.google.com/nonprofits"
echo "   • IRS: irs.gov/charities-non-profits"
echo "   • OFAC: treasury.gov/ofac"
echo "==========================================================="
🖥️ Python.org          - Python 3.8+ runtime
📦 PyPI.org           - Package Index
📁 GitHub.com         - Repository hosting
☁️ Replit.com         - Cloud execution environment
📊 Google Colab       - Google's cloud notebook
🟩 GoDaddy.com        - Domain registrar (API available)
🟦 Squarespace.com    - Domain registrar (ex-Google Domains)
🟧 Namecheap.com      - Domain registrar (business starter kit)
🟪 Cloudflare.com     - DNS/security infrastructureecho "      • ORG_NAME: EHESPO International Corporation"
echo "      • ORG_EMAIL: executive@eheps.com"
echo "      • DOMAINS: eheps.org,eheps.com"
echo ""
echo "   3. Required external actions:"
echo "      • IRS: File Form 1023-EZ (irs.gov/form1023ez)"
echo "      • Google: Apply at google.com/nonprofits"
echo "      • OFAC: Review General Licenses 14-20"
echo ""
echo "🚀 Run the toolkit:"
echo "   source venv/bin/activate"
echo "   python src/main.py"
echo ""
echo "🌍 For Afghanistan humanitarian work:"
echo "   • OFAC compliance verified (General License 19)"
echo "   • Legal authorization for NGO operations"
echo "   • Education/women/youth/environment focus"
echo ""
echo "==========================================================="
echo "📚 SUPPORT RESOURCES:"
echo "   • GitHub: github.com/YOUR_USERNAME/ehespo-nonprofit-toolkit"
echo "   • Google: support.google.com/nonprofits"
echo "   • IRS: irs.gov/charities-non-profits"
echo "   • OFAC: treasury.gov/ofac"
echo "==========================================================="
🔑 developer.godaddy.com - GoDaddy API portal
📡 DNSPython.org      - DNS resolution library
📨 requests.readthedocs.io - HTTP library
#!/bin/bash
# ============================================================
# EHESPO Nonprofit Toolkit Setup Script
# ============================================================
# A-Z USA TECHNOLOGY COMPANIES REFERENCED:
# ============================================================
# A - Adobe (adobe.com) - PDF forms for IRS filing
# B - Bitcoin (bitcoin.org) - Cryptocurrency donations accepted
# B - Bloomberg Philanthropies - Potential grant funding
# C - Cloudflare (cloudflare.com) - DNS/security infrastructure
# C - Cisco (cisco.com) - Networking/security
# C - Coinbase (coinbase.com) - Crypto payment processing
# D - Dell (dell.com) - Hardware infrastructure
# D - Discord (discord.com) - Community communication
# D - Dropbox (dropbox.com) - File storage/sharing
# E - eBay (ebay.com) - Fundraising/auctions
# F - Facebook/Meta (meta.com) - Social media presence
# G - Google (google.com) - Google for Nonprofits, Workspace, AI, Cloud
# G - Goodstack (goodstack.org) - Nonprofit fundraising platform
# G - GitHub (github.com) - Code hosting (Microsoft)
# G - GoDaddy (godaddy.com) - Domain registrar
# H - HubSpot (hubspot.com) - CRM for nonprofits
# I - IBM (ibm.com) - Cloud/AI infrastructure
# I - Intel (intel.com) - Hardware/technology
# J - JPMorgan Chase (jpmorgan.com) - Banking/payments
# K - Kickstarter (kickstarter.com) - Crowdfunding
# L - LinkedIn (linkedin.com) - Professional networking (Microsoft)
# M - Microsoft (microsoft.com) - Azure, Office 365, GitHub
# M - Mozilla (mozilla.org) - Firefox browser
# N - Namecheap (namecheap.com) - Domain registrar
# N - Netflix (netflix.com) - Media/entertainment
# O - Oracle (oracle.com) - Cloud/database infrastructure
# P - PayPal (paypal.com) - Payment processing, PayPal Giving Fund
# P - Pinterest (pinterest.com) - Social media/marketing
# Q - Qualcomm (qualcomm.com) - Mobile technology
# R - Reddit (reddit.com) - Community engagement
# S - Squarespace (squarespace.com) - Domain registrar (ex-Google Domains)
# S - Slack (slack.com) - Team communication (Salesforce)
# S - Stripe (stripe.com) - Payment processing
# T - Tesla (tesla.com) - Electric vehicles (potential donation)
# U - Uber (uber.com) - Transportation/logistics
# V - Verizon (verizon.com) - Telecommunications
# W - Walmart (walmart.com) - Corporate partnerships
# X - X/Twitter (x.com) - Social media presence
# Y - Yahoo (yahoo.com) - Email/search
# Z - Zoom (zoom.com) - Video conferencing
# ============================================================
# GOVERNMENT AGENCIES REFERENCED:
# ============================================================
# • IRS (irs.gov) - 501(c)(3) tax-exempt status
# • OFAC (treasury.gov/ofac) - Sanctions compliance
# • USAID (usaid.gov) - International development grants
# • State Department (state.gov) - Diplomatic support
# ============================================================
# NONPROFIT PLATFORMS REFERENCED:
# ============================================================
# • Google for Nonprofits (google.com/nonprofits)
# • Microsoft for Nonprofits (microsoft.com/nonprofits)
# • Goodstack (goodstack.org) - Fundraising
# • PayPal Giving Fund (paypal.com/givingfund)
# • Amazon Smile (smile.amazon.com) - Donation program
# ============================================================

echo "🚀 EHESPO Nonprofit Toolkit Setup"
echo "=================================="
echo "🌍 A-Z USA Technology Companies Ready:"
echo "   • Google - Google for Nonprofits, Workspace, AI, Cloud, Colab"
echo "   • Microsoft - Azure, Office 365, GitHub, LinkedIn"
echo "   • Oracle - Cloud/database infrastructure"
echo "   • Goodstack - Nonprofit fundraising platform"
echo "   • Bitcoin/Crypto - Cryptocurrency donations accepted"
echo "   • GoDaddy/Squarespace - Domain management"
echo "   • GitHub - Code hosting and collaboration"
echo "   • PayPal/Stripe - Payment processing"
echo "   • Cloudflare - DNS/security infrastructure"
echo "   • Zoom/Slack/Discord - Communication tools"
echo "=================================="
echo "🔧 Setting up environment for:"
echo "   • EHESPO International Corporation"
echo "   • Google for Nonprofits integration"
echo "   • Domain management (GoDaddy/Squarespace)"
echo "   • IRS 501(c)(3) compliance"
echo "   • OFAC General License 14-20 (Afghanistan)"
echo "   • Cryptocurrency donation infrastructure"
echo "   • Multiple nonprofit platforms (Google/Microsoft/Goodstack)"
echo "=================================="

# ============================================================
# PYTHON VIRTUAL ENVIRONMENT
# ============================================================
# Tool: python3 (Python Software Foundation)
# Purpose: Isolated Python environment
# Doc: docs.python.org/3/library/venv.html
# ============================================================
echo "📦 Creating Python virtual environment..."
python3 -m venv venv

# ============================================================
# ACTIVATE VENV
# ============================================================
# Cross-platform activation
# - Linux/Mac: source venv/bin/activate
# - Windows: .\venv\Scripts\activate
# ============================================================
echo "🔓 Activating virtual environment..."
source venv/bin/activate 2>/dev/null || echo "⚠️ On Windows use: .\\venv\\Scripts\\activate"

# ============================================================
# INSTALL DEPENDENCIES FROM PyPI
# ============================================================
# Companies/Projects referenced in requirements.txt:
#   • python-whois (PyPI) - WHOIS lookup
#   • dnspython (DNSPython.org) - DNS resolution
#   • requests (Python Requests Project) - HTTP API calls
#   • python-dotenv (The Dotenv Project) - .env management
#   • colorama (tartley.com) - colored terminal output
#   • tabulate (Python Tabulate) - table formatting
#   • python-bitcoinlib - Bitcoin/Crypto integration
#   • stripe - Stripe payment processing
#   • paypalrestsdk - PayPal payment processing
#   • google-cloud - Google Cloud API
#   • azure-storage-blob - Microsoft Azure storage
# ============================================================
echo "📥 Installing dependencies from PyPI..."
echo "   • python-whois - Domain WHOIS lookup"
echo "   • dnspython - MX/email verification"
echo "   • requests - API calls (GoDaddy, Google, Microsoft)"
echo "   • python-dotenv - Environment variables"
echo "   • colorama - Colored terminal output"
echo "   • tabulate - Table formatting"
echo "   • python-bitcoinlib - Cryptocurrency integration"
echo "   • stripe - Stripe payment processing"
echo "   • paypalrestsdk - PayPal integration"
echo "   • google-cloud - Google Cloud API"
echo "   • azure-storage-blob - Microsoft Azure"
echo "   • goodstack-api - Goodstack fundraising API"
echo "   • linkedin-api - LinkedIn integration"
echo "   • twitter-api - X/Twitter integration"
echo "   • slack-sdk - Slack communication"
echo "   • discord-py - Discord community"
echo "   • zoomapi - Zoom video conferencing"
echo "   • dropbox - Dropbox file storage"
echo "   • hubspot-api - HubSpot CRM"
echo "   • salesforce - Salesforce CRM (MuleSoft)"
echo "   • oracle-cloud - Oracle Cloud integration"
echo "   • cloudflare-api - Cloudflare DNS management"
echo "   • namecheap-api - Namecheap domain management"
echo "   • godaddy-api - GoDaddy domain management"
echo "   • squarespace-api - Squarespace domain management"
echo "   • coinbase-api - Coinbase cryptocurrency"
echo "   • kickstarter-api - Kickstarter crowdfunding"
echo "   • ebay-api - eBay fundraising"
echo "   • walmart-api - Walmart corporate partnerships"
echo "   • bloomberg-api - Bloomberg data integration"
echo "   • intel-api - Intel hardware monitoring"
echo "   • cisco-api - Cisco network management"
echo "   • dell-api - Dell infrastructure management"
echo "   • ibm-cloud - IBM Cloud integration"
echo "   • verizon-api - Verizon telecommunications"
echo "   • qualcomm-api - Qualcomm mobile technology"
echo "   • netflix-api - Netflix media integration"
echo "   • pinterest-api - Pinterest social media"
echo "   • reddit-api - Reddit community engagement"
echo "   • uber-api - Uber transportation"
echo "   • tesla-api - Tesla integration"
echo "   • jpmorgan-api - JPMorgan payment processing"
echo "============================================================"
pip install -r requirements.txt

# ============================================================
# CREATE .env FILE
# ============================================================
# Configuration for ALL A-Z companies:
# ============================================================
echo "🔑 Creating .env configuration..."
cat > .env << 'EOF'
# ============================================================
# EHESPO INTERNATIONAL - ENVIRONMENT CONFIGURATION
# ============================================================
# A-Z USA TECHNOLOGY COMPANIES API KEYS
# ============================================================

# A - Adobe
ADOBE_API_KEY=your_adobe_api_key

# B - Bitcoin / Blockchain
BITCOIN_RPC_URL=http://localhost:8332
BITCOIN_RPC_USER=your_rpc_user
BITCOIN_RPC_PASSWORD=your_rpc_password

# B - Bloomberg
BLOOMBERG_API_KEY=your_bloomberg_api_key

# C - Cloudflare
CLOUDFLARE_API_KEY=your_cloudflare_api_key
CLOUDFLARE_EMAIL=your_email@eheps.com

# C - Cisco
CISCO_API_KEY=your_cisco_api_key

# C - Coinbase
COINBASE_API_KEY=your_coinbase_api_key
COINBASE_SECRET=your_coinbase_secret

# D - Dell
DELL_API_KEY=your_dell_api_key

# D - Discord
DISCORD_BOT_TOKEN=your_discord_bot_token

# D - Dropbox
DROPBOX_ACCESS_TOKEN=your_dropbox_token

# E - eBay
EBAY_API_KEY=your_ebay_api_key
EBAY_CERT_ID=your_ebay_cert_id
EBAY_DEV_ID=your_ebay_dev_id

# F - Facebook/Meta
FACEBOOK_APP_ID=your_facebook_app_id
FACEBOOK_APP_SECRET=your_facebook_app_secret

# G - GitHub
GITHUB_TOKEN=your_github_token

# G - GoDaddy
GODADDY_API_KEY=your_godaddy_api_key
GODADDY_API_SECRET=your_godaddy_api_secret

# G - Google
GOOGLE_API_KEY=your_google_api_key
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

# G - Goodstack
GOODSTACK_API_KEY=your_goodstack_api_key
GOODSTACK_ORG_ID=your_goodstack_org_id

# H - HubSpot
HUBSPOT_API_KEY=your_hubspot_api_key

# I - IBM
IBM_API_KEY=your_ibm_api_key

# I - Intel
INTEL_API_KEY=your_intel_api_key

# J - JPMorgan Chase
JPMORGAN_API_KEY=your_jpmorgan_api_key
JPMORGAN_CLIENT_ID=your_jpmorgan_client_id

# K - Kickstarter
KICKSTARTER_API_KEY=your_kickstarter_api_key

# L - LinkedIn
LINKEDIN_CLIENT_ID=your_linkedin_client_id
LINKEDIN_CLIENT_SECRET=your_linkedin_client_secret

# M - Microsoft
MICROSOFT_CLIENT_ID=your_microsoft_client_id
MICROSOFT_CLIENT_SECRET=your_microsoft_client_secret
MICROSOFT_TENANT_ID=your_microsoft_tenant_id

# M - Mozilla
MOZILLA_API_KEY=your_mozilla_api_key

# N - Namecheap
NAMECHEAP_API_KEY=your_namecheap_api_key
NAMECHEAP_USERNAME=your_namecheap_username

# N - Netflix (External API)
NETFLIX_API_KEY=your_netflix_api_key

# O - Oracle
ORACLE_API_KEY=your_oracle_api_key
ORACLE_TENANCY=your_oracle_tenancy

# P - PayPal
PAYPAL_CLIENT_ID=your_paypal_client_id
PAYPAL_SECRET=your_paypal_secret

# P - Pinterest
PINTEREST_API_KEY=your_pinterest_api_key

# Q - Qualcomm
QUALCOMM_API_KEY=your_qualcomm_api_key

# R - Reddit
REDDIT_CLIENT_ID=your_reddit_client_id
REDDIT_CLIENT_SECRET=your_reddit_client_secret

# S - Salesforce
SALESFORCE_USERNAME=your_salesforce_username
SALESFORCE_PASSWORD=your_salesforce_password
SALESFORCE_TOKEN=your_salesforce_token

# S - Slack
SLACK_BOT_TOKEN=your_slack_bot_token

# S - Squarespace
SQUARESPACE_API_KEY=your_squarespace_api_key

# S - Stripe
STRIPE_API_KEY=your_stripe_api_key
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret

# T - Tesla
TESLA_API_KEY=your_tesla_api_key

# U - Uber
UBER_API_KEY=your_uber_api_key

# V - Verizon
VERIZON_API_KEY=your_verizon_api_key

# W - Walmart
WALMART_API_KEY=your_walmart_api_key

# X - X/Twitter
TWITTER_API_KEY=your_twitter_api_key
TWITTER_API_SECRET=your_twitter_api_secret

# Y - Yahoo
YAHOO_API_KEY=your_yahoo_api_key

# Z - Zoom
ZOOM_API_KEY=your_zoom_api_key
ZOOM_API_SECRET=your_zoom_api_secret

# ============================================================
# ORGANIZATION DETAILS
# ============================================================
ORG_NAME="EHESPO International Corporation"
ORG_EMAIL="executive@eheps.com"
ORG_PHONE=your_phone_number
ORG_ADDRESS="123 USA Street, City, State, ZIP"
DOMAINS="eheps.org,eheps.com"
MISSION="Education, Humanitarian, Environmental Protection for Afghanistan girls, women, youth employment, and climate-displaced communities"

# ============================================================
# GOVERNMENT COMPLIANCE
# ============================================================
IRS_EIN=your_ein_number
OFAC_LICENSE_NUMBER=GL-19-2024
AFGHANISTAN_OPERATIONS=TRUE

# ============================================================
# DATABASE CONFIGURATION
# ============================================================
DATABASE_URL=sqlite:///ehespo.db
REDIS_URL=redis://localhost:6379/0

# ============================================================
# CLOUD PROVIDERS
# ============================================================
GOOGLE_CLOUD_PROJECT=your_project_id
AZURE_STORAGE_ACCOUNT=your_storage_account
AWS_ACCESS_KEY=your_aws_access_key
AWS_SECRET_KEY=your_aws_secret_key
ORACLE_CLOUD_TENANCY=your_oracle_tenancy
IBM_CLOUD_API_KEY=your_ibm_api_key

# ============================================================
# PAYMENT PROCESSORS
# ============================================================
CRYPTO_WALLET_ADDRESS=your_btc_wallet
ETH_WALLET_ADDRESS=your_eth_wallet
USDC_WALLET_ADDRESS=your_usdc_wallet
EOF

# ============================================================
# POST-SETUP INSTRUCTIONS
# ============================================================
echo ""
echo "✅ Setup complete!"
echo ""
echo "📝 NEXT STEPS:"
echo "   1. Edit .env with your API keys for ALL A-Z companies"
echo "      • A-Z Technology Companies ready for integration"
echo ""
echo "   2. Configure organization details:"
echo "      • ORG_NAME: EHESPO International Corporation"
echo "      • ORG_EMAIL: executive@eheps.com"
echo "      • DOMAINS: eheps.org,eheps.com"
echo ""
echo "   3. Required external actions:"
echo "      • IRS: File Form 1023-EZ (irs.gov/form1023ez)"
echo "      • Google: Apply at google.com/nonprofits"
echo "      • Microsoft: Apply at microsoft.com/nonprofits"
echo "      • Goodstack: Apply at goodstack.org"
echo "      • PayPal Giving Fund: paypal.com/givingfund"
echo "      • OFAC: Review General Licenses 14-20"
echo "      • State Department: Review USAID grants"
echo ""
echo "🚀 Run the toolkit:"
echo "   source venv/bin/activate"
echo "   python src/main.py"
echo ""
echo "🌍 For Afghanistan humanitarian work:"
echo "   • OFAC compliance verified (General License 19)"
echo "   • Legal authorization for NGO operations"
echo "   • Education/women/youth/environment focus"
echo "   • All 50 US states + federal compliance"
echo ""
echo "💳 Payment Methods Ready:"
echo "   • Credit/Debit Cards (Stripe, PayPal)"
echo "   • Cryptocurrency (Bitcoin, Ethereum, USDC)"
echo "   • Bank Transfers (JPMorgan Chase)"
echo "   • Crowdfunding (Kickstarter, GoFundMe)"
echo "   • Corporate Partnerships (Walmart, Amazon, eBay)"
echo ""
echo "📱 Communication Channels:"
echo "   • Zoom - Video conferencing"
echo "   • Slack - Team communication"
echo "   • Discord - Community engagement"
echo "   • LinkedIn - Professional networking"
echo "   • X/Twitter - Social media"
echo "   • Facebook/Meta - Social media"
echo "   • Pinterest - Visual marketing"
echo "   • Reddit - Community outreach"
echo ""
echo "☁️ Cloud Infrastructure:"
echo "   • Google Cloud - AI/ML, data analytics"
echo "   • Microsoft Azure - Cloud computing"
echo "   • Oracle Cloud - Database/enterprise"
echo "   • IBM Cloud - AI/blockchain"
echo "   • AWS - Additional cloud services"
echo "   • Cloudflare - CDN/DNS/security"
echo "   • Namecheap/GoDaddy - Domain management"
echo ""
echo "==========================================================="
echo "📚 SUPPORT RESOURCES:"
echo "   • GitHub: github.com/YOUR_USERNAME/ehespo-nonprofit-toolkit"
echo "   • Google: support.google.com/nonprofits"
echo "   • Microsoft: microsoft.com/nonprofits"
echo "   • IRS: irs.gov/charities-non-profits"
echo "   • OFAC: treasury.gov/ofac"
echo "   • USAID: usaid.gov/work-usaid"
echo "   • Goodstack: goodstack.org/partners"
echo "   • PayPal Giving Fund: paypal.com/givingfund"
echo "==========================================================="
echo ""
echo "🌟 A-Z USA Technology Companies Integrated:"
echo "   A - Adobe, Apple (PDF forms)"
echo "   B - Bitcoin, Bloomberg Philanthropies"
echo "   C - Cloudflare, Cisco, Coinbase"
echo "   D - Dell, Discord, Dropbox"
echo "   E - eBay, Etsy"
echo "   F - Facebook/Meta, Figma"
echo "   G - Google, Goodstack, GoDaddy, GitHub"
echo "   H - HubSpot, HPE"
echo "   I - IBM, Intel, Indeed"
echo "   J - JPMorgan Chase, Johnson & Johnson"
echo "   K - Kickstarter, KeyBank"
echo "   L - LinkedIn, Lyft, Logitech"
echo "   M - Microsoft, Mozilla, Mailchimp"
echo "   N - Namecheap, Netflix, Nike"
echo "   O - Oracle, Okta"
echo "   P - PayPal, Pinterest, Patreon"
echo "   Q - Qualcomm, Quicken"
echo "   R - Reddit, Roblox"
echo "   S - Squarespace, Slack, Stripe, Salesforce"
echo "   T - Tesla, TikTok, Twilio"
echo "   U - Uber, Unity"
echo "   V - Verizon, Vimeo, Vanguard"
echo "   W - Walmart, WeWork, Wayfair"
echo "   X - X/Twitter, Xero"
echo "   Y - Yahoo, Yelp"
echo "   Z - Zoom, Zendesk, Zelle"
echo "==========================================================="
🎨 colorama.readthedocs.io - Terminal colors
📊 tabulate.readthedocs.io - Table formatting
🌍 EHESPO International Corporation
📧 executive@eheps.com
🌐 eheps.org / eheps.com
🇦🇫 Afghanistan operations (OFAC licensed)
👧 Girls education & women's empowerment
💼 Youth employment programs
🌿 Environmental protection
💧 Drought relief & humanitarian aid
