# 🇨🇦 Vancouver 2026

Interactive travel itinerary for Sep 16-28, 2026 trip to Vancouver Island, BC.

## ✨ Features

✅ **Live countdown timer** - Auto-updating every second  
✅ **Complete itinerary** - 13-day day-by-day breakdown  
✅ **Flight details** - Toronto ↔ Vancouver  
✅ **Accommodation info** - All bookings listed  
✅ **Dark/Light mode** - Auto-detected based on system preference  
✅ **Mobile responsive** - Optimized for all devices  
✅ **Offline accessible** - Works without internet  
✅ **Zero dependencies** - Pure HTML/CSS/JS  

## 🚀 Quick Deploy on Cloudflare Workers

### Prerequisites
- Cloudflare account ([sign up free](https://dash.cloudflare.com))
- Node.js & npm installed
- GitHub account

### Deploy Steps

1. **Clone this repository**
   ```bash
   git clone https://github.com/chejingxuancar-prog/vancouver-trip-2026.git
   cd vancouver-trip-2026
   ```

2. **Install dependencies**
   ```bash
   npm install -g @cloudflare/wrangler
   npm install
   ```

3. **Authenticate with Cloudflare**
   ```bash
   wrangler login
   ```

4. **Deploy to Cloudflare Workers**
   ```bash
   wrangler deploy
   ```

5. **Your site is now live at:**
   ```
   https://vancouver-trip-2026.chejingxuancar-prog.workers.dev
   ```

### 🛠️ Local Development

Test locally before deploying:
```bash
wrangler dev
```

Then visit `http://localhost:8787`

## 📋 Content Structure

- **Countdown Card** - Live timer to departure (Sep 16, 2026 11:00 AM)
- **Flights** - Outbound & return flight details
- **Accommodation** - 5 hotels/Airbnbs listed
- **Daily Itinerary** - Complete 13-day breakdown (Sep 16-28)
- **To-Do Checklist** - Pre-trip tasks
- **Tips & Important Info** - Tide times, ferry schedules, timezone conversions

## 📍 Trip Highlights

### Vancouver (Sep 16-20)
- Waterfront Walk & Gastown
- Stanley Park bike ride
- Flyover Canada
- Dr. Sun Yat-Sen Chinese Garden
- Granville Island or UBC

### Ucluelet (Sep 20-22)
- Wild Pacific Trail
- Rainforest Trail A & B
- Ucluelet Harbour Kayaking Tour

### Qualicum Beach & Union Bay (Sep 22-24)
- Goat on the Roof (Coombs)
- Little Qualicum Cheeseworks
- **Oyster digging** at Union Bay (low tide 1:29 PM Sep 24)

### Gabriola Island (Sep 24-25)
- Gabriola Sands Provincial Park
- Drumbeg Park
- Malaspina Galleries
- Local cafés & art galleries

### Return to Vancouver (Sep 25-28)
- Grouse Mountain (details TBD)
- Lynn Valley Suspension Bridge (details TBD)
- Final departure Sep 28 at 3:25 PM

## ⏰ Timezone Info

- **Toronto:** EDT (UTC-4)
- **Vancouver:** PDT (UTC-7)
- **Time Difference:** 3 hours (Vancouver is behind)

## 🌊 Important Tide Information

- **Sep 23:** Low tide @ 6:14 PM (-4.3 ft) - Backup oyster digging
- **Sep 24:** Low tide @ 1:29 PM (-0.7 m) - Primary oyster digging time
- **Reference:** Gabriola Island tide table

## 🚗 Car Rental

- **Pickup:** Nanaimo Airport (Sep 20)
- **Dropoff:** Nanaimo (Sep 25)
- **Duration:** 6 days
- **Route:** Nanaimo → Ucluelet → Qualicum → Union Bay → Gabriola → Nanaimo → Vancouver

## 🚤 Ferry Information

- **Nanaimo ↔ Gabriola Island**
  - Frequency: Every 40-60 minutes
  - Duration: 20-25 minutes
  - Operator: BC Ferries

- **Nanaimo ↔ Vancouver (Horseshoe Bay)**
  - Duration: 1 hour 40 minutes
  - Wait times: +30-60 minutes (peak season)

## 📱 Responsive Design

- Mobile-first approach
- Works on all screen sizes
- Dark mode auto-detection
- Accessible color contrast
- Touch-friendly buttons

## 🛠️ Technologies

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Hosting:** Cloudflare Workers (Serverless)
- **Deployment:** Wrangler CLI
- **Dependencies:** None (Zero external libraries)
- **Performance:** Ultra-fast, globally distributed

## 📝 Notes

- **Update Status:** Itinerary framework complete
- **Pending Details:** Sep 26-27 activities (Grouse Mountain, Lynn Valley) - To be added
- **Hotel Modifications Needed:**
  - Qualicum Bay Resort: Change dates from Sep 22-23 to Sep 22-24 (extend 1 night)
- **Bookings Pending:**
  - Gabriola Island Airbnb (Sep 24-25)
  - Vancouver Airport Hotel (Sep 25-26)

## 📞 Support

For Cloudflare Workers issues:
- [Cloudflare Workers Docs](https://developers.cloudflare.com/workers/)
- [Wrangler CLI Guide](https://developers.cloudflare.com/workers/wrangler/)

---

**Created:** Generated for Sep 16-28, 2026 trip  
**Deployed on:** Cloudflare Workers  
**Last Updated:** 2026  
🎒 Ready for your Vancouver Island adventure!
