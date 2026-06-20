here.. 
Mm/#!/bin/bash
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
