# Pedigree → Kellogg's cross-sell demo

A clickable WhatsApp prototype for a Freestand cross-sell journey.

A happy Pedigree sample claimant (someone who left positive feedback in an
earlier chat) receives a WhatsApp push offer, taps to accept, and is handed
off to a Kellogg's chatbot that collects a few preferences and the delivery
address before confirming the free sample.

## Run it

Open `index.html` in any browser — it's a single self-contained file, no build
step or dependencies.

## Flow

1. **Pedigree chat** — thanks the claimant for 5-star feedback, then sends the
   push: *"We think we've got a special offer for you — and we reckon you'll
   love Kellogg's. Would you like to claim a free sample?"*
2. **Accept** — tapping the offer redirects the conversation to the Kellogg's
   chatbot.
3. **Kellogg's journey** — pick a sample, say who it's for, re-enter the
   delivery address and mobile number, review a summary, and confirm.

All data shown (name, address, phone) is placeholder demo content.
