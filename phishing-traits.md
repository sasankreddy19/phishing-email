# Phishing Traits Summary

**Sample**: PayPal Phishing Email (`paypal_phishing_sample.eml`)

**Traits Identified**:
1. **Spoofed Sender**: `security@paypal-support.com` mimics PayPal but uses a fraudulent domain.
2. **Header Discrepancies**: `Return-Path` (`noreply@randomdomain.xyz`) and originating IP do not match PayPal’s servers.
3. **Suspicious Link**: Displayed URL (`https://paypal.com/verify`) links to `http://secure-paypal-login.xyz/verify`.
4. **Urgent Language**: “Verify within 24 hours or your account will be suspended” creates panic.
5. **Mismatched URLs**: Displayed URL differs from actual destination, leading to a fake login page.
6. **Spelling/Grammar Errors**: “verfiy” instead of “verify,” “informations” instead of “information.”
7. **Impersonation**: Poses as PayPal to exploit trust.

**Conclusion**: The email uses classic phishing tactics to trick users into visiting a malicious site and entering credentials.
