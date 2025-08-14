# ayan-test
import React from "react";
import { motion } from "framer-motion";

// Single-file, production-ready landing page component
// TailwindCSS-based; drop into any React/Next project. No external UI kit required.
// Replace VSL src/hrefs with your real links + connect CTAs to your booking flow.

export default function RealEstateAccessLP() {
  return (
    <div className="min-h-screen bg-white text-neutral-900">
      {/* Sticky Top Nav */}
      <header className="sticky top-0 z-50 w-full border-b border-neutral-200 bg-white/80 backdrop-blur">
        <div className="mx-auto flex max-w-7xl items-center justify-between px-4 py-3">
          <a href="#top" className="flex items-center gap-2">
            <div className="h-7 w-7 rounded-lg bg-neutral-900" />
            <span className="text-sm font-semibold tracking-wide">BEN MALLAH ACCESS</span>
          </a>
          <nav className="hidden items-center gap-6 md:flex">
            <a href="#truth" className="text-sm hover:text-neutral-600">Why Most Fail</a>
            <a href="#story" className="text-sm hover:text-neutral-600">Ben's Story</a>
            <a href="#method" className="text-sm hover:text-neutral-600">Mallah Method</a>
            <a href="#options" className="text-sm hover:text-neutral-600">Access Options</a>
            <a href="#testimonials" className="text-sm hover:text-neutral-600">Proof</a>
            <a href="#faq" className="text-sm hover:text-neutral-600">FAQ</a>
          </nav>
          <a href="#book" className="rounded-xl bg-neutral-900 px-4 py-2 text-sm font-semibold text-white hover:bg-neutral-800">Book Now</a>
        </div>
      </header>

      {/* Hero */}
      <section id="top" className="relative overflow-hidden">
        <div className="pointer-events-none absolute inset-0 -z-10 bg-[radial-gradient(60%_50%_at_50%_0%,#f5f5f5,transparent)]" />
        <div className="mx-auto grid max-w-7xl items-center gap-10 px-4 py-12 md:grid-cols-2 md:py-20">
          <div>
            <motion.h1
              initial={{ opacity: 0, y: 20 }}
              animate={{ opacity: 1, y: 0 }}
              transition={{ duration: 0.5 }}
              className="text-3xl font-extrabold leading-tight md:text-5xl"
            >
              For Serious Real Estate Investors Who Are Done Playing Small
              <span className="block text-neutral-600">Scale Your Portfolio to $10M+ in 24 Months</span>
              <span className="block text-neutral-600">With Direct Access to a $500 Million Real Estate Mogul</span>
            </motion.h1>
            <p className="mt-4 max-w-xl text-base text-neutral-600 md:text-lg">
              Without the costly mistakes, analysis paralysis, or gut-wrenching fear that your next deal could be a financial disaster.
            </p>
            <div className="mt-6 flex flex-wrap items-center gap-3">
              <a href="#book" className="rounded-2xl bg-neutral-900 px-6 py-3 text-sm font-semibold text-white shadow-sm hover:bg-neutral-800">
                GET DIRECT ACCESS TO BEN NOW
              </a>
              <a href="#vsl" className="rounded-2xl border border-neutral-300 px-6 py-3 text-sm font-semibold hover:bg-neutral-50">
                Watch the VSL
              </a>
            </div>
            <div className="mt-6 flex items-center gap-4 text-xs text-neutral-500">
              <span>Over $1B moved in real estate</span>
              <span>•</span>
              <span>Hotels, Shopping Centers, Multifamily</span>
              <span>•</span>
              <span>Florida Operator</span>
            </div>
          </div>

          {/* VSL Placeholder */}
          <div id="vsl" className="relative aspect-video w-full overflow-hidden rounded-2xl border border-neutral-200 shadow-sm">
            <div className="absolute inset-0 grid place-items-center bg-neutral-50">
              <div className="text-center">
                <div className="mx-auto mb-3 h-14 w-14 rounded-full bg-neutral-900" />
                <p className="text-sm font-semibold">[ VSL PLACEHOLDER ]</p>
                <p className="mt-1 text-xs text-neutral-500">Embed your video player here</p>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* Section: Brutal Truth */}
      <section id="truth" className="border-t border-neutral-200 bg-neutral-50">
        <div className="mx-auto max-w-5xl px-4 py-14 md:py-20">
          <h2 className="text-2xl font-extrabold md:text-4xl">The Brutal Truth About Why 97% of Real Estate Investors Never Break Past $2 Million in Assets</h2>
          <div className="prose prose-neutral mt-6 max-w-none text-[15px] leading-7">
            <p>You've got a few rental properties under your belt. Maybe even a small apartment building. The cash flow is... decent. Not life-changing, but decent.</p>
            <p>But here's what's eating at you every single night... You <strong>KNOW</strong> there's a massive leap between where you are now and where the real money is made.</p>
            <p>The difference between owning 5 properties and owning 500. Between collecting $5,000 a month in rent and collecting $50,000.</p>
            <p><strong>The problem isn't your hustle.</strong> It's not your capital. It's not even the market. <strong>The problem is you're flying blind in a game where one wrong move can wipe out everything you've built.</strong></p>
            <p>Every deal feels like Russian roulette. Every property inspection makes your stomach drop. Every financing conversation leaves you wondering if you're about to get played.</p>
            <p>And the "gurus" out there? They're selling you cookie-cutter strategies that worked in 2015... maybe.</p>
            <p>What you need isn't another course or seminar. You need someone who's actually DONE IT to look you in the eye and tell you exactly what move to make next.</p>
          </div>
          <div className="mt-8">
            <a href="#book" className="inline-flex items-center justify-center rounded-xl bg-neutral-900 px-5 py-3 text-sm font-semibold text-white hover:bg-neutral-800">Book Your Access Call</a>
          </div>
        </div>
      </section>

      {/* Section: Story */}
      <section id="story" className="border-t border-neutral-200">
        <div className="mx-auto grid max-w-7xl items-center gap-10 px-4 py-16 md:grid-cols-2">
          <div className="order-2 md:order-1">
            <h2 className="text-2xl font-extrabold md:text-4xl">How a Broke Kid from Queens Built a $500 Million Empire</h2>
            <div className="prose prose-neutral mt-5 max-w-none text-[15px] leading-7">
              <p>Twenty-five years ago, I was washing dishes in Queens. Today, I control over $500 million in real estate across Florida. Hotels. Shopping centers. Apartment complexes. Properties that generate more cash flow in a month than most people see in a year.</p>
              <p>But here's the thing nobody tells you about building an empire... <strong>Every single breakthrough came from making the "wrong" decision that turned out to be exactly right.</strong></p>
              <p>While other investors were playing it safe with single-family homes, I was buying distressed hotels. While they were analyzing deals to death, I was closing on properties in 48 hours. While they were following the textbook, I was writing my own playbook.</p>
              <p>The conventional wisdom? It's designed to keep you small. The real money, the life-changing wealth, the financial freedom that lets you sleep like a baby... that comes from knowing which rules to break and when. And after moving over $1 billion in real estate, I've figured out the exact formula.</p>
              <p>The question is: Are you ready to skip the 10-year learning curve and get it directly from someone who's already won the game?</p>
            </div>
          </div>
          <div className="order-1 md:order-2">
            <div className="aspect-[4/5] w-full overflow-hidden rounded-2xl border border-neutral-200 bg-neutral-100 shadow-inner" />
          </div>
        </div>
      </section>

      {/* Section: Mallah Method */}
      <section id="method" className="border-t border-neutral-200 bg-neutral-50">
        <div className="mx-auto max-w-6xl px-4 py-16">
          <h2 className="text-2xl font-extrabold md:text-4xl">The "Mallah Method": Why Direct Access Beats Any Course</h2>
          <div className="prose prose-neutral mt-5 max-w-none text-[15px] leading-7">
            <p>Here's what I've learned after 25 years in this game: Real estate isn't about formulas. It's about <strong>FEEL</strong>. You can't learn "feel" from a YouTube video or a $97 course.</p>
            <p>You get it from sitting across the table from someone who's already made every mistake you're about to make. When I look at a deal, I can tell you in 30 seconds if it's a goldmine or a money pit—not because I'm psychic, but because I've seen this movie 10,000 times.</p>
            <p>I know which markets are about to explode, which properties will cash flow, and which contractors will make or break you. Most importantly, I know exactly what you should do next to get from where you are to where you want to be.</p>
            <p>That knowledge? That instinct? That network? You can't Google it. You can't buy it in a book. For the first time ever, I'm making it available to serious investors ready to play in the big leagues.</p>
          </div>
        </div>
      </section>

      {/* Section: Offers */}
      <section id="options" className="border-t border-neutral-200">
        <div className="mx-auto max-w-7xl px-4 py-16">
          <div className="mx-auto mb-10 max-w-2xl text-center">
            <h2 className="text-2xl font-extrabold md:text-4xl">Four Ways to Get Direct Access</h2>
            <p className="mt-2 text-neutral-600">Choose your level of commitment.</p>
          </div>

          <div className="grid gap-6 md:grid-cols-2 lg:grid-cols-4">
            {/* Option 1 */}
            <OfferCard
              title="The Strategy Call"
              price="15m $349 | 30m $699"
              bullets={[
                "Deal analysis, market pick, strategy",
                "Send details beforehand",
                "No fluff. Exact next move",
              ]}
              ctaText="Book Strategy Call"
            />
            {/* Option 2 */}
            <OfferCard
              title="The Mansion Meeting"
              price="2 Hours • $5,000"
              bullets={[
                "At my $30M estate (Tampa Bay)",
                "Deep portfolio review over lunch",
                "Access to network & contacts",
              ]}
              ctaText="Reserve Mansion Meeting"
            />
            {/* Option 3 */}
            <OfferCard
              title="Shadow Ben Experience"
              price="4 Hours • $15,000"
              bullets={[
                "On-site property visits",
                "Meet contractors & PMs",
                "See live deal decisions",
              ]}
              ctaText="Apply to Shadow Ben"
            />
            {/* Option 4 */}
            <OfferCard
              title="Multifamily Mastermind"
              price="Sept 2025 • Belleair Beach, FL"
              bullets={[
                "Limited to 20 investors",
                "Dinner $4,999 | Private +$4,000",
                "2 days intensive + network",
              ]}
              ctaText="Join the Mastermind"
            />
          </div>
        </div>
      </section>

      {/* Section: Pricing Logic */}
      <section className="border-t border-neutral-200 bg-neutral-50">
        <div className="mx-auto grid max-w-6xl gap-10 px-4 py-16 md:grid-cols-2">
          <div>
            <h3 className="text-xl font-extrabold md:text-2xl">Why Paying $699 for 30 Minutes Is the Smartest Financial Decision You'll Make This Year</h3>
            <div className="prose prose-neutral mt-4 max-w-none text-[15px] leading-7">
              <p>One bad deal can cost you $100,000+. One missed opportunity can cost you millions. I've seen it happen both ways.</p>
              <p>The difference? Information. Experience. Instinct. For less than a weekend seminar, you get 30 minutes of specific guidance from someone who has actually built what you're trying to build.</p>
              <p>One conversation can save a six-figure mistake. One insight can unlock a seven-figure opportunity. If I can't help you, I'll tell you straight up.</p>
            </div>
          </div>
          <div className="rounded-2xl border border-neutral-200 p-6 shadow-sm">
            <ul className="space-y-3 text-sm">
              <li className="flex items-start gap-3"><span className="mt-1 h-2 w-2 rounded-full bg-neutral-900" /> How much will trial & error cost you?</li>
              <li className="flex items-start gap-3"><span className="mt-1 h-2 w-2 rounded-full bg-neutral-900" /> How many years will you waste on outdated strategies?</li>
              <li className="flex items-start gap-3"><span className="mt-1 h-2 w-2 rounded-full bg-neutral-900" /> What's it worth to skip mistakes and go straight to what works?</li>
            </ul>
            <a href="#book" className="mt-6 inline-flex w-full justify-center rounded-xl bg-neutral-900 px-5 py-3 text-sm font-semibold text-white hover:bg-neutral-800">Book Your Session</a>
          </div>
        </div>
      </section>

      {/* Section: Testimonials */}
      <section id="testimonials" className="border-t border-neutral-200">
        <div className="mx-auto max-w-6xl px-4 py-16">
          <h2 className="text-2xl font-extrabold md:text-4xl">What Serious Investors Are Saying…</h2>
          <div className="mt-8 grid gap-6 md:grid-cols-3">
            <TestimonialCard
              quote="I was stuck at 12 units for three years. One call with Ben changed everything. Six months later, I closed on a 48‑unit complex. Best $699 I've ever spent."
              name="Michael R."
              location="Tampa"
            />
            <TestimonialCard
              quote="The mansion meeting was incredible. Ben introduced me to his PM, lender, and contractor. That network alone has been worth millions."
              name="Sarah T."
              location="Orlando"
            />
            <TestimonialCard
              quote="I thought $15k to shadow Ben was crazy—then I watched him negotiate a $200k reno savings. Cheapest education I've ever had."
              name="David L."
              location="Jacksonville"
            />
          </div>
        </div>
      </section>

      {/* Section: FAQ */}
      <section id="faq" className="border-t border-neutral-200 bg-neutral-50">
        <div className="mx-auto max-w-5xl px-4 py-16">
          <h2 className="text-2xl font-extrabold md:text-4xl">Frequently Asked Questions</h2>
          <div className="mt-6 grid gap-4 md:grid-cols-2">
            <FAQItem q="Is this really worth the money?" a="If you're worried about $349, you're not ready for this. This is for investors who know the right info at the right time is priceless." />
            <FAQItem q="What if I don't like your advice?" a="Then don't take it. I'm not your coach. I'm an operator sharing exactly how I built it. Take it or leave it." />
            <FAQItem q="Can't I just watch your YouTube videos?" a="You can, and you can try surgery by watching TV. Real results come from specific, applied guidance on your exact situation." />
            <FAQItem q="What makes you different from gurus?" a="I'm not a guru. I make money DOING real estate. This is about helping serious investors avoid the mistakes I made." />
            <FAQItem q="Is this some kind of scam?" a="I've got a $500M portfolio. I don't need a few hundred bucks. This is about legacy and helping the next generation build wealth." />
          </div>
        </div>
      </section>

      {/* Section: Steps + Final CTA */}
      <section id="book" className="border-t border-neutral-200">
        <div className="mx-auto grid max-w-6xl items-start gap-10 px-4 py-16 md:grid-cols-2">
          <div>
            <h2 className="text-2xl font-extrabold md:text-4xl">Here's What Happens When You Book Today</h2>
            <ol className="mt-6 space-y-3 text-sm">
              {[
                "Choose your level of access",
                "Complete booking & send your deal details",
                "Receive confirmation & next steps",
                "Get direct access to 25 years of mastery",
                "Take action on specific guidance",
                "Build the portfolio you've dreamed of",
              ].map((step, i) => (
                <li key={i} className="flex items-start gap-3">
                  <span className="mt-1 inline-flex h-5 w-5 items-center justify-center rounded-full bg-neutral-900 text-[11px] font-bold text-white">{i + 1}</span>
                  <span>{step}</span>
                </li>
              ))}
            </ol>
            <p className="prose prose-neutral mt-6 text-[15px] leading-7">
              The window for this kind of access won't stay open forever. I'm not building a coaching business. I'm making myself available to a select group of serious investors who are ready to stop playing small.
            </p>
            <p className="mt-4 text-sm font-semibold">This isn't for everyone—it's for the 3% ready to stop making excuses and start making millions.</p>
          </div>
          <div className="rounded-2xl border border-neutral-200 p-6 shadow-sm">
            <h3 className="text-lg font-bold">Book Your Session with Ben Now</h3>
            <form className="mt-4 space-y-3">
              <input className="w-full rounded-xl border border-neutral-300 px-3 py-2 text-sm outline-none focus:ring-2 focus:ring-neutral-900" placeholder="Full Name" />
              <input type="email" className="w-full rounded-xl border border-neutral-300 px-3 py-2 text-sm outline-none focus:ring-2 focus:ring-neutral-900" placeholder="Email" />
              <input className="w-full rounded-xl border border-neutral-300 px-3 py-2 text-sm outline-none focus:ring-2 focus:ring-neutral-900" placeholder="Phone" />
              <select className="w-full rounded-xl border border-neutral-300 px-3 py-2 text-sm outline-none focus:ring-2 focus:ring-neutral-900">
                <option>Choose Access Option</option>
                <option>Strategy Call — 15m ($349)</option>
                <option>Strategy Call — 30m ($699)</option>
                <option>Mansion Meeting — 2h ($5,000)</option>
                <option>Shadow Ben — 4h ($15,000)</option>
                <option>Mastermind — Dinner ($4,999)</option>
                <option>Mastermind — Private Meeting ($8,999)</option>
              </select>
              <textarea className="h-28 w-full rounded-xl border border-neutral-300 px-3 py-2 text-sm outline-none focus:ring-2 focus:ring-neutral-900" placeholder="Share your deal details / questions"></textarea>
              <button type="button" className="w-full rounded-xl bg-neutral-900 px-5 py-3 text-sm font-semibold text-white hover:bg-neutral-800">Complete Booking</button>
              <p className="text-xs text-neutral-500">You're not charged here. This is a demo UI. Connect to your checkout (Stripe/Calendly) in production.</p>
            </form>
            <div className="mt-6 text-xs text-neutral-500">— Ben Mallah</div>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="border-t border-neutral-200">
        <div className="mx-auto flex max-w-7xl flex-col items-center justify-between gap-4 px-4 py-8 md:flex-row">
          <p className="text-xs text-neutral-500">© {new Date().getFullYear()} Ben Mallah Access. All rights reserved.</p>
          <div className="flex items-center gap-4 text-xs text-neutral-500">
            <a href="#" className="hover:text-neutral-700">Terms</a>
            <a href="#" className="hover:text-neutral-700">Privacy</a>
            <a href="#top" className="hover:text-neutral-700">Back to top</a>
          </div>
        </div>
      </footer>

      {/* Mobile Sticky CTA */}
      <div className="fixed inset-x-0 bottom-0 z-50 border-t border-neutral-200 bg-white/90 p-3 backdrop-blur md:hidden">
        <a href="#book" className="block w-full rounded-xl bg-neutral-900 py-3 text-center text-sm font-semibold text-white">Book Your Session</a>
      </div>
    </div>
  );
}

function OfferCard({ title, price, bullets, ctaText }: { title: string; price: string; bullets: string[]; ctaText: string; }) {
  return (
    <div className="flex h-full flex-col justify-between rounded-2xl border border-neutral-200 p-6 shadow-sm">
      <div>
        <h3 className="text-lg font-bold">{title}</h3>
        <p className="mt-1 text-sm text-neutral-600">{price}</p>
        <ul className="mt-4 space-y-2 text-sm">
          {bullets.map((b, i) => (
            <li key={i} className="flex items-start gap-3"><span className="mt-1 h-2 w-2 rounded-full bg-neutral-900" /> {b}</li>
          ))}
        </ul>
      </div>
      <a href="#book" className="mt-6 inline-flex justify-center rounded-xl bg-neutral-900 px-4 py-2 text-sm font-semibold text-white hover:bg-neutral-800">{ctaText}</a>
    </div>
  );
}

function TestimonialCard({ quote, name, location }: { quote: string; name: string; location: string; }) {
  return (
    <div className="rounded-2xl border border-neutral-200 p-6 shadow-sm">
      <p className="text-sm leading-6">“{quote}”</p>
      <div className="mt-4 text-xs text-neutral-500">— {name}, {location}</div>
    </div>
  );
}

function FAQItem({ q, a }: { q: string; a: string; }) {
  return (
    <details className="rounded-xl border border-neutral-200 bg-white p-4">
      <summary className="cursor-pointer text-sm font-semibold">{q}</summary>
      <p className="mt-2 text-sm text-neutral-600">{a}</p>
    </details>
  );
}
