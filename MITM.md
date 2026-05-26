# Man in the Middle Attack — The Silent Eavesdropper

The attacker sits between you
and everything you trust.

## What is a MITM Attack?
Attacker secretly intercepts communication
between two parties without either knowing.

You think you're talking to your bank.
You're actually talking to the attacker.

## How it Works
Normal:
You ←————————→ Bank

MITM:
You ←——→ Attacker ←——→ Bank

1. You connect to public WiFi
2. Attacker intercepts your traffic
3. Reads passwords & messages
4. Can modify what you send
5. Neither side notices anything

## Types of MITM Attacks
ARP Spoofing       tricks devices on local network
DNS Spoofing       redirects to fake websites
SSL Stripping      downgrades HTTPS to HTTP
WiFi Eavesdropping fake hotspot captures traffic
Session Hijacking  steals logged-in session cookie

## Real Scenario
You sit at a cafe.
Connect to "Free_CafeWiFi" (created by attacker).
Open bank website.
Attacker strips HTTPS to HTTP.
You log in normally.

Attacker captures:
→ Username & password
→ Session cookie
→ Account details

Account — EMPTIED.

## Signs You're Being Attacked
→ Sudden SSL certificate warnings
→ Website looks slightly different
→ Unexpected logouts from accounts
→ HTTP instead of HTTPS on secure sites
→ Unusual account activity

## How to Stay Safe
→ Never use public WiFi for sensitive tasks
→ Always check for HTTPS padlock
→ Use a VPN on public networks
→ Enable 2FA on all accounts
→ Don't ignore SSL warnings
→ Use mobile data instead of public WiFi

"You're never really alone
on a public network."
