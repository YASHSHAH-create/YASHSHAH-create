<p align="center">
  <img src="assets/hero.svg" width="100%" alt="Yash Shah. Full-stack and mobile engineer building Paymm." />
</p>

<p align="center">
  <a href="https://www.paymm.in"><img src="https://img.shields.io/badge/WEB-paymm.in-FF4A1C?style=flat-square&labelColor=0A0A0B" alt="paymm.in" /></a>
  <a href="https://play.google.com/store/apps/details?id=in.paymm.app"><img src="https://img.shields.io/badge/PLAY-Paymm-FF4A1C?style=flat-square&labelColor=0A0A0B" alt="Paymm on Google Play" /></a>
  <a href="https://apps.apple.com/in/app/id6780256299"><img src="https://img.shields.io/badge/APP_STORE-Paymm-FF4A1C?style=flat-square&labelColor=0A0A0B" alt="Paymm on the App Store" /></a>
  <a href="https://www.linkedin.com/in/yash-shah-a83797273"><img src="https://img.shields.io/badge/LINKEDIN-yash--shah-FF4A1C?style=flat-square&labelColor=0A0A0B" alt="LinkedIn" /></a>
  <a href="https://instagram.com/_yash_shah__"><img src="https://img.shields.io/badge/INSTAGRAM-__yash__shah____-FF4A1C?style=flat-square&labelColor=0A0A0B" alt="Instagram" /></a>
</p>

<p align="center">
  <strong>Yash Shah</strong> · Full-stack and mobile developer · React Native, Node.js, Go · Indore, India
</p>

I'm Yash Shah, a full-stack developer from Indore. I build **Paymm**, an Indian super-app where one wallet pays for mobile recharges, bills, FASTag, flights, hotels, buses and bike-taxi rides. I write the React Native apps, the Node and Go services behind them, and the release pipeline that gets a fix onto phones the same day.

Most of that code is private, so the contribution graph says more than the repo list does.

## In production

<p>
  <a href="https://www.paymm.in"><img src="assets/card-paymm.svg" width="49%" alt="Paymm: recharge, bills, FASTag, flights, hotels, buses and rides behind one wallet. Live on iOS, Android and web." /></a>
  <a href="https://play.google.com/store/apps/details?id=in.paymm.captain"><img src="assets/card-captain.svg" width="49%" alt="Paymm Captain: the driver app for Paymm Ride. Live on iOS and Android." /></a>
</p>
<p>
  <img src="assets/card-ride.svg" width="49%" alt="Ride Dispatch: the Go service behind Paymm Ride. Matching, fares and live trip tracking over WebSockets." />
  <img src="assets/card-recharge.svg" width="49%" alt="Recharge Engine: routes every recharge and bill across several providers and hands over when one fails." />
</p>
<p>
  <a href="https://github.com/YASHSHAH-create/lvs-livestream-backend"><img src="assets/card-lvs.svg" width="49%" alt="LVS Live: backend for live streams and group voice rooms over Socket.IO and LiveKit. Public repo." /></a>
  <img src="assets/card-heymilo.svg" width="49%" alt="HeyMilo: a dating app with an Expo client and a Go backend. In build." />
</p>

## How it fits together

<p align="center">
  <img src="assets/system.svg" width="100%" alt="System map: four clients talk to eight services, which sit on MongoDB, Postgres and Redis, a payment gateway, supplier APIs and push." />
</p>

## Things I had to get right

- **A recharge that fails at one provider is retried at the next** before the user ever sees an error. If every route says no, the money is back in the wallet without a support ticket.
- **A driver's phone rings full-screen for a new ride even when the app is killed.** Dispatch is push-first, so a swiped-away app still gets the trip.
- **Hotel results arrive batch by batch.** The list fills in as each supplier answers instead of waiting on the slowest one.
- **One JavaScript fix reaches three store versions the same day.** Every over-the-air update is built against each live runtime, so nobody is left on a broken build waiting for review.
- **A payment page that hangs does not strand the user.** If the in-app gateway stalls, checkout falls back to the browser and the booking still completes.

## Toolbox

<p align="center">
  <img src="assets/stack.svg" width="100%" alt="Toolbox. Mobile: React Native, Expo, TypeScript, Reanimated, EAS and OTA. Backend: Node.js, Express, Go, Gin, WebSocket, Socket.IO. Data: MongoDB, Postgres, Redis. Web: Next.js, React, Vercel. Infra: AWS EC2, PM2, Cloudflare, GitHub Actions, Firebase. Web3: Solana, smart contracts." />
</p>

<p align="center">
  <sub>Indore, India · open to hard problems in payments, travel and real-time systems · <a href="https://www.linkedin.com/in/yash-shah-a83797273">say hi</a></sub>
</p>
