# Analysis: RTT vs. Speed-of-Light

## 1. Which city has the highest inefficiency ratio? What cables serve it and how does that explain your result?

- **City:** Frankfurt (Ratio: 3.61)
- **Cables:** Frankfurt is a huge internet hub with tons of cables (see submarinecablemap.com). Even so, my RTT was way higher than the theoretical minimum. This is probably due to indirect routing, congestion, or just how real-world networks work—packets don't always take the shortest path.

## 2. Which city is closest to the theoretical minimum? What does that tell you about routing infrastructure there?

- **City:** Sydney (Ratio: 1.22)
- **Explanation:** Sydney's RTT is really close to the minimum, which means the routing is super efficient. Australia has modern, direct cables to Asia and the US, so the network there is well-optimized with few detours.

## 3. Why does Africa route through Europe, and what would need to change to fix it?

Most traffic to Lagos goes through Europe because most cables from Africa land there, and Europe is a global internet hub. There aren't many direct cables from Africa to the Americas or Asia.

**To fix this:**
- Build more direct cables from Africa to other continents
- Invest in local African IXPs and peering
- Improve regional infrastructure to avoid unnecessary detours
