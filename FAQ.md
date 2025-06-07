# Frequently Asked Questions (FAQ)

Welcome to The Hazzard Continuum! We're excited you're here. This document should answer some of the initial questions you might have about the project.

---

### General Questions

**What is The Hazzard Continuum?**

The Hazzard Continuum is an alternative system for measuring daily life, built on the principles of logic, consistency, and human-centric design. It consists of three parts:

1.  **The Continuum Calendar:** A 13-month perennial calendar.
2.  **Universal Time:** A single, global time for everyone (UTC).
3.  **Hazzen Temperature:** A temperature scale based on human comfort.

The goal is to provide a more intuitive and future-proof way to think about our days, while our app provides the tools to use it and convert to legacy systems.

**Is this a joke?**

No. While the project has a sense of humor, it is a serious exploration of a "what-if" scenario. It's a fully thought-out system designed to be logical and consistent. Think of it as a functional thought experiment.

**Is there an intention to make this a global standard or encourage people to use this for real life?**

No, that is not a realistic goal. It is more of a fun, philosophical discussion about what the future could be. Changing the entire world to use a new system would be next to impossible due to cultural and logistical inertia.

That being said, it is designed so you _could_ use it all by yourself if you wanted to! The primary goal of the app is to provide the tools that would allow an individual to adopt it for their own life while still being able to seamlessly interact with the rest of the world.

**Does the creator use this in real life?**

Absolutely not. The creator enjoys building the system and exploring the concepts, but still has to schedule meetings and buy groceries in the real world using the Gregorian calendar and local time, just like everyone else.

**Why create a new system? Isn't the Gregorian standard good enough?**

The current systems have quirks and historical baggage that create unnecessary complexity. Timezone math is a common source of confusion, and the Gregorian calendar is irregular. This project is a practical proposal for a system designed from the ground up for a modern, interconnected world. For a full breakdown of the project's philosophy, see our [Decision Document](./standard/DECISIONS.md).

**How can I start using The Hazzard Continuum?**

The easiest way is to use our web app! It provides a dashboard with the current Continuum date, time, and temperature, along with converters and tools to help you bridge the gap between this system and the global standard.

---

### The Continuum Calendar

**Why 13 months of 28 days?**

This structure creates a _perennial_ (or "fixed") calendar.

-   Every month has exactly 4 weeks.
-   Every date (e.g., the 15th) falls on the same day of the week, every single year.
-   This makes scheduling and planning incredibly simple and predictable.

**Why does the year start on March 1st?**

This is a nod to the original Roman calendar, where March was the first month. It also aligns the start of the year more closely with the vernal equinox for the Northern Hemisphere, which feels like a more natural beginning.

**What is "Gormanuary" and who is Dave Gorman?**

The 13th month, Gormanuary, is named in honor of comedian and writer Dave Gorman. His brilliant and hilarious explanation of a 13-month calendar system was a major inspiration for this project. We highly recommend [watching his segment on the topic](https://www.youtube.com/watch?v=vunESk53r5U).

**What happens to my birthday?**

Your birthday still happens once a year! It will have a new date in the Continuum Calendar. You can use the converter in our app to find your new birthday. The best part? It will be on the same day of the week for the rest of your life!

**What are "Intermission" days?**

A year of 13 months of 28 days is \(13 \times 28 = 364\) days. "Intermission" is the 365th day of the year. It doesn't belong to any month or any day of the week. Think of it as a special year-end holiday. On leap years, there are two Intermission days. This is what keeps the calendar perfectly aligned with the solar year.

---

### Universal Time

**Why use UTC for everything? Won't it be confusing if my "noon" is at 17:00?**

It might feel strange at first, but the goal is to eliminate ambiguity. 14:00 is 14:00 for everyone, everywhere. No more "Is that my time or your time?". You quickly learn to associate certain UTC times with your local solar events (sunrise, noon, sunset). The app's "Day Arc" visualization is designed specifically to help you build this intuition.

**Isn't this just what pilots and scientists already do?**

Yes, exactly! They use UTC (or GMT) because it's robust, unambiguous, and essential for coordinating complex operations. The Hazzard Continuum proposes that this benefit shouldn't be limited to specialists—it can simplify life for everyone in a globally connected world.

---

### Hazzen Temperature

**Why create a new temperature scale? Why not just use Celsius?**

Celsius is a scientific scale, centered on the properties of water (0°C for freezing, 100°C for boiling). The Hazzen scale is a _human-centric_ scale. Its reference point is based on the primary reason most people check the weather: to know how it will feel and what they should wear.

**What is 0 H based on? Why 66°F?**

\(0 \text{ H}\) is set to \(66^\circ\text{F}\) (or about \(19^\circ\text{C}\)). This was chosen as a baseline for "comfortable room temperature" or "light sweater weather." This way, positive numbers mean "it's getting warm," and negative numbers mean "it's getting cool." The scale is simple: \(1 \text{ H} = 4^\circ\text{F}\).

**Is the Hazzen scale useful for science?**

No, and it's not intended to be. Celsius and Kelvin are superior for scientific work. The Hazzen scale is designed for everyday life.

---

### Contributing & Project Details

**How can I contribute to the project?**

We'd love your help! The best place to start is by reading our [CONTRIBUTING.md](./CONTRIBUTING.md) file, which outlines how to report bugs, request features, and submit changes to the code or the standard itself.

**Is the standard "final"? Can it be changed?**

The standard is not set in stone. It is an open proposal governed by an RFC process. We encourage discussion and formal proposals for changes in our GitHub repository.

**What's the license? Can I use this in my own project?**

The Hazzard Continuum is licensed under the [MIT License](./LICENSE). This is a very permissive license that allows you to use, copy, modify, and distribute the project freely, for both private and commercial use, as long as you include the original copyright and license notice.
