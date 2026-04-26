# gestionepagine.com

Sito corporate di **Gestione Pagine SRL** — hub digital factory del gruppo GP SRL.

## Stato attuale

🚧 **Maintenance page live** durante migrazione da WordPress (ManagedServer) a sito statico su Cloudflare Pages.

## Stack

- HTML/CSS statico, single-file
- Cloudflare Pages (auto-deploy da `main`)
- Mailchimp embedded form (audience `0f70f27559`, group `Aziendale > Gestionepagine Corporate`)
- Font: Fraunces (display, Google Fonts) + Inter (body) + JetBrains Mono (caption)

## Identità visiva

Palette corporate digital factory (no terra/ink/rame ecosistema turistico Castelluccio):

| Ruolo | Hex |
|---|---|
| Background | `#FAFAF7` |
| Ink (testo) | `#0F1419` |
| Ink soft | `#5A5F66` |
| Primary | `#1E3A5F` |
| Ocra (accent) | `#C9A227` |
| Line | `#E5E5E0` |

## Branch operative del gruppo

1. Digital Factory
2. Marketing & Performance
3. Logistica & Spedizioni (DeliveryExpress)
4. Manifattura Luxury (FaconiItalia)
5. Real Estate
6. Sostenibilità & Territorio (cross-cutting: Resto in Piedi, La Casa Sull'Albero ODV, Castelluccio 1452, Strategic Foresight)

## Standard ecosistema

- Bottom bar v1.3 (3-block colophon + 6° tazzina PayPal)
- Cookie GDPR sotto PEC GP SRL
- Coerenza tecnica (no estetica) con gli altri 7 siti dell'ecosistema

## Email infrastructure

- Caselle email su Register.it (6 attive + PEC)
- DNS records replicati 1:1 da Register su Cloudflare al momento dello switch nameserver
- MX, SPF, autoconfig, autodiscover SRV, authsmtp tutti replicati

## Roadmap

- [x] Maintenance page v1
- [ ] Switch DNS Register → Cloudflare
- [ ] Cancellazione DB ManagedServer (dopo 1-2 settimane stabilità email)
- [ ] Sito corporate completo (7 sezioni)
- [ ] Migrazione email a provider con DKIM/DMARC propri (deliverability upgrade)

---

**Gestione Pagine SRL** · Via Cellulosa 25 · 00166 Roma · CF/P.IVA 14388161003
