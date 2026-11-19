# Hi, I'm David

I'm an agentic engineer in Mesa, Arizona. AI agents write most of my code now, and I own everything around it: the goal, the plan, the questions, the tests and the final call. The agents are fast. My job is to make sure they build the right thing and that it holds up after it ships.

I've been shipping iOS apps since 2010. These days I build AI agent systems, ship with them, and teach other engineers to work this way.

At CallRail I built a team of AI agents that builds a full vendor integration, from the API client to the frontend, and reviews its own code. It has shipped 13 integrations to production, and work that used to take about a week now gets to code review in under a day.

Everything else happens at [Red Mesa Studios](https://redmesastudios.com), my independent studio for AI agents, automated systems and apps.

## AI agents and tools

- **[Project Dispatcher](https://github.com/dbarkman/ProjectDispatcher)** is an open-source orchestration harness that runs a team of AI agents on a Kanban board. A project manager agent turns my idea into a design and a phased plan. Coding, code review, security review, merge and deploy agents carry each ticket from there, and an engineering manager agent monitors the whole flow.
- **[SignalPost](https://signalpost.redmesastudios.com)** groups articles from 130+ newsrooms into stories and ranks them by how many outlets cover them. It runs as a public MCP server and JSON API, so any AI agent can pull top stories, search them or ask about one.
- **Clark** is my personal AI agent, built in Python on the Claude Agent SDK and MCP. We talk through Telegram. He reads my email, sends a daily digest and follows the news through SignalPost. He's built security-first: per-session tool allowlists, read-and-label-only email access, an append-only action log and secrets in the Keychain.
- **[ClaudeMeter](https://github.com/dbarkman/ClaudeMeter)** is a macOS menu bar meter for Claude plan usage, so I can pace a long day without opening the usage screen.
- **[AI News HQ](https://github.com/dbarkman/ainews)** is a topic-matched AI news aggregator with a deliberate volume cap. It's live at [ainews.redmesastudios.com](https://ainews.redmesastudios.com).
- **[SleeperFFL](https://github.com/dbarkman/SleeperFFL)** is a draft assistant and waiver-wire watcher for Sleeper fantasy football leagues. It ranks players by value over replacement using the league's own scoring, and pushes waiver alerts to my phone.
- **[Clams](https://github.com/dbarkman/Clams)** is the code behind [cla.ms](https://cla.ms), a small, friendly URL shortener. It has a site, a JSON API, click stats that never store IP addresses, and a browser extension for Chrome and Safari.
- **ScrollForge** is a text RPG run entirely by an AI game master. The GM narrates, voices every character and decides consequences from a world bible. Players can bring their own API key or pick from six AI providers.

## Apps

- **Morsel** (in progress) is an iPhone and Apple Watch health tracker where the agent is the product. It logs meals from photos, labels and weights, builds reports, and redesigns the app's screens, cards and goals.
- **[Just Drink](https://github.com/dbarkman/JustDrink)** is a simple water tracker for iPhone and iPad, built with SwiftUI, SwiftData and CloudKit. Tilt the phone and the water sloshes.
- **[SimpleTV](https://github.com/dbarkman/SimpleTV)** is a calm Android TV home screen I built for my family, with no ads or autoplay. It has search across every service, a YouTube feed, weather, news and market cards, and a family photo screensaver. I run it on an Onn 4k streaming stick from Walmart: https://cla.ms/2zylQv, but it should run fine on any Android TV stick, just ask your favorite AI agent to help you set it up.
- **[Imposter](https://github.com/dbarkman/Imposter)** is a party word game for Android TV. Everyone joins from their phone's browser, with nothing to install.
- **[Trivia Night](https://github.com/dbarkman/TriviaNight)** is a family trivia game for Android TV. Play solo with the remote, or together: the TV shows a QR code and everyone answers on their own phone, with nothing to install. It has five levels, from grade school to expert, and dozens of categories.
- **Every Earthquake** and **BareWeather** are on the App Store. The [original Every Earthquake iOS source](https://github.com/dbarkman/everyearthquake-ios) is here too.
- **[Patchwork Valley](https://github.com/dbarkman/PatchworkValley)** is a calm hex puzzle game for iOS, with a SwiftUI HUD over a SpriteKit board. Every game rule lives in a tested Swift package, and levels are seeded so they always deal the same tiles.
- **[Far Markets](https://github.com/dbarkman/FarMarkets)** is a trading game for phones that you can [play in the browser](https://trader.redmesastudios.com). Travel between markets across three eras: the Age of Sail, the Silk Road and space.
- **[SimpleCalc](https://github.com/dbarkman/SimpleCalc)** is a small Mac calculator with glass buttons that works entirely from the keyboard.
- **KiteTails**, a 3D puzzle game, is coming soon.

## How I work

I teach the same process I use: set the goal and how you'll know it worked, let the agent ask questions until it gets it, build in small phases and test every one. I also run AI training for engineering teams, and you can [join the waitlist](https://redmesastudios.com/training).

Before this I spent years leading teams. Turns out leading agents is a lot like leading people: get close to the people with the problem, figure out what they actually need, build it and own it in production.

If you're building that kind of team, I'm always up to compare notes. You can find me through [redmesastudios.com](https://redmesastudios.com).

And yes, I wrote this with Claude. ;)
