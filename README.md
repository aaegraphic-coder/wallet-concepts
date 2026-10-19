# Stablecoin wallet concepts

Five clickable UX concepts for making a USDT wallet feel safe, simple and useful for everyday people in Indonesia.

**Live demo:** https://aaegraphic-coder.github.io/wallet-concepts/

![Preview](preview.png)

## The ideas

| # | Concept | Problem | Hypothesis | How I'd measure it |
|---|---|---|---|---|
| 1 | **Send without picking a network** | Sending USDT means choosing a network. Pick one the recipient can't receive on and the money can be lost. | If the wallet picks a network both sides support, wrong-network losses drop and first-time senders finish more often. | Wrong-network support tickets, send completion rate, time to "Arrived". |
| 2 | **Look-alike address check** | Address poisoning plants look-alike addresses in your history. People only check the first and last few characters. | Showing the exact difference and making the saved address the default stops most poisoned sends without slowing normal ones. | Sends to flagged addresses, % who switch to the saved address, cancels during the 10-minute hold, false-alarm rate. |
| 3 | **Request in Rupiah** | Freelancers price in Rupiah while clients pay in USDT, so amounts end up wrong. | A Rupiah request with a locked rate and one link gets people paid the right amount, faster. | Links paid in full, time to payment, follow-up messages per request. |
| 4 | **Backup without the fear** | Many people skip backup or store their words unsafely, and fake "support" accounts ask for them. | Explaining first, one quick quiz and an encrypted default raise backup completion without raising phishing risk. | Backup completion in week one, quiz correct on first try, successful restores. |
| 5 | **Pay QRIS with USDT** (new) | People hold USDT as savings, but daily life in Indonesia runs on QRIS in Rupiah. | Converting to Rupiah at the moment of payment, through a licensed partner, makes USDT useful every day while the merchant just receives Rupiah. | QRIS payments per active user per week, failed payments at the till, seconds from scan to paid. |

### What you can try

- Keypad amounts, press-and-hold to send, networks the recipient can't use are blocked with a reason, and the balance updates afterwards.
- Character-by-character address comparison and a cancellable 10-minute hold.
- Rupiah slider with a locked rate, QR and share sheet, then a live "waiting for payment" state.
- A live password check, or 12 words that stay blurred until you hold to reveal them, verified with three taps.
- A QRIS scan, Rupiah keypad with a 000 key, a locked 30-second rate, and a receipt in both currencies. "Scan" on the wallet home opens it.

A design note beside the phone explains the reasoning behind each screen.

**Note on concept 5:** in Indonesia crypto can't be used as a payment instrument, so in this concept the merchant never receives USDT. A licensed partner converts it to Rupiah first. A real version would need legal and compliance review.

## About

Designed by Angga Ady Ermawan, Senior Product Designer. Built as a single HTML file with AI-assisted prototyping tools.

These are personal concepts. Not affiliated with or endorsed by any wallet provider. Fees, exchange rates, names, merchants and QR codes are examples only.
