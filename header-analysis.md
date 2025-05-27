# Email Header Analysis

**Tool Used**: MXToolbox Email Header Analyzer

**Key Findings**:
- **From**: `security@paypal-support.com` (spoofed, not PayPal’s official domain)
- **Return-Path**: `noreply@randomdomain.xyz` (mismatch with sender domain)
- **Received**: Originating IP [192.168.x.x] not associated with PayPal servers
- **Message-ID**: `<abc123@randomdomain.xyz>` (non-standard, suggests phishing)
- **X-Mailer**: Generic mailer, not typical of corporate email systems

**Conclusion**: Headers indicate spoofing, as the sender’s domain and server origins do not align with PayPal’s infrastructure.
