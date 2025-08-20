---
layout: splash
title: ""
permalink: /
author_profile: false
classes: wide
toc: false
---
<style>
/* ============ Universal expander behavior (Services, About, Training) ============ */
.expander summary {
  display: flex;                 /* lets us push the right icon to the edge */
  align-items: center;
  gap: .4rem;
  cursor: pointer;
  list-style: none;
  width: 100%;                   /* ensure the right icon has space to align right */
}
.expander summary::-webkit-details-marker { display: none; }

/* Right-aligned icon for ALL expanders */
.expander summary::after { content: "+"; margin-left: auto; }
.expander[open] summary::after { content: "–"; }

/* (If you still have inline left "+" spans in About/Training, this just bolds them) */
.expander .plus { font-weight: 700; }

/* ============ Services spacing ============ */
#services .service-list {
  margin: 1rem 0 1rem 1.5rem;    /* space above & below list */
  padding-left: .5rem;
  font-size: .95rem;
  line-height: 1.55;
}
#services .service-list li + li { margin-top: .75rem; }
#services .exp-note { margin-top: 1rem; }

/* ============ Training spacing ============ */
#training .training-list {
  margin: 1rem 0 0 1.5rem;       /* space above list */
  padding-left: .5rem;
  font-size: .95rem;
  line-height: 1.55;
}
#training .training-list li { margin-bottom: .75rem; }

/* ============ About (optional tiny top margin when open) ============ */
#about #about-expander[open] { margin-top: .5rem; }
/* ===== Featured cards: responsive grid ===== */
/* Desktop default: 3 columns */
.card-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1rem;
}

/* Tablet: 2 columns */
@media (max-width: 1024px) {
  .card-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

/* Mobile: 1 column */
@media (max-width: 640px) {
  .card-grid {
    grid-template-columns: 1fr;
  }
}

/* Safety: prevent overflow from long titles/text */
.card-grid > * { min-width: 0; }
</style>

<!-- Hero Section -->
<header class="hero">
  <h1 style="margin-bottom: 0;">Kathryn Karnell</h1>
  <p style="font-size: 1.2em; margin-top: 0;">
    Communications Strategist and Content Creator
  </p>
  <p><em>I help you clarify your goals, create content, and achieve results. As your human in the loop, I adapt & evolve with the latest technology to optimize content quality and achieve measurable success.
  Let’s work together to move from your BackStory to your ForwardStory!</em></p>
<p>📬 <a href="mailto:forwardstory@gmail.com">forwardstory@gmail.com</a></p>
</header>

<!-- Navigation Links -->
<nav class="jump-links">
<!-- What I Do -->
<section id="services">
  <h2>What I Can Do for You</h2>

  <p>
    I work with organizations, teams, and individuals to clarify your communication goals and develop a strategy that gets you where you want to go.
    When you bring me in, I’ll assess what’s working, identify the gaps, and deliver a tailored package of messaging, content, and tools that help you reach your goals — clearly, effectively, and with your audience in mind.
  </p>

  <details class="expander" id="services-expander">
    <summary>Core services include: <span class="plus" aria-hidden="true">+</span></summary>

    <ul class="service-list">
      <li><strong>🟣 Content Strategy &amp; Planning</strong> — I’ll review your content ecosystem, audit what's working, and develop a roadmap to align content with your brand and audience needs.</li>
      <li><strong>🟣 Messaging &amp; Content Packages</strong> — Marketing materials, website content, newsletters, executive messaging, campaign copy, or storytelling frameworks — all tailored to your voice, audience, and goals.</li>
      <li><strong>🟣 AI Integration &amp; Team Training</strong> — Many workplaces feel pressure to use AI without a clear path. I help teams build literacy, pick the right tools, and use AI to create better, more efficient content — with intention, not urgency.</li>
    </ul>

    <p class="exp-note"><em>Need something not listed here? Let’s talk – I shape my services around your real needs.</em></p>
  </details>
</section>



<!-- About -->
<section id="about">
  <h2>About Me</h2>

  <p>I’m a communications strategist with a proven record of helping organizations clarify complex ideas and connect with the people they serve. My background spans government, global health, public service, mission-driven work, and small business needs — including projects with CDC, USAID, Deloitte, Peace Corps, University of Washington, and Johns Hopkins.</p>

  <details class="expander" id="about-expander">
    <summary>Learn a little more about me <span class="plus" aria-hidden="true">+</span></summary>

    <p>I’ve worked across six countries and three continents, always focused on making communication more effective, accessible, and meaningful.</p>

    <p>I’ve helped teams define their core messages, write for multiple audiences, and manage the content needed for newsletters, websites, and campaigns. I’ve also led training sessions and supported teams as they adapt to organizational needs or new tools — like AI — to improve their workflows and outcomes.</p>

    <p>I don’t overpromise. I help you figure out what’s essential, what’s working, and what needs to change — then I help you do something about it.</p>
  </details>
</section>


<!-- Featured Work -->
<section id="portfolio">
<h2>Featured Work</h2>
<p>Over the course of my career, I’ve created varied products from educational documentaries, social media campaigns, press releases, talking points, and written stories to website overhauls, newsletters, and fact sheets. I’ve designed and delivered training. These sample projects reflect a blend of content strategy, messaging development, and AI-assisted delivery. Curious about what else I've done, read this list of sample projects. Or, view my resume.</p>

<div class="card-grid" style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 1.5em;">

  <!-- Card 1 -->
  <div class="card" style="flex: 1 1 calc(33% - 1em); box-shadow: 0 0 5px rgba(0,0,0,0.1); border-radius: 8px; overflow: hidden; background: #fff; padding: 1em;">
    <img src="/assets/images/be-inspired-facebook.jpg" alt="Black Maternal Health Week thumbnail" style="width: 100%; border-radius: 6px;">
    <h4>Black Maternal Health Week - Integrated Campaign</h4>
    <p>Pioneered and executed a multi-channel campaign, integrating social, video, and written stories, boosting digital engagement and strengthening partner relationships.</p>
    <p><a href="#">Learn more</a></p>
  </div>

  <!-- Card 2 -->
  <div class="card" style="flex: 1 1 calc(33% - 1em); box-shadow: 0 0 5px rgba(0,0,0,0.1); border-radius: 8px; overflow: hidden; background: #fff; padding: 1em;">
    <img src="/assets/images/Destiny600X315.jpg" alt="Doula story thumbnail" style="width: 100%; border-radius: 6px;">
    <h4><em>This is Destiny</em> – The Power of Doula Care for Better Health</h4>
    <p>Doula support helped mom advocate for her needs, foster positive relationships with her doctor, and achieve improved physical and mental health.</p>
    <p><a href="#">Read the story</a></p>
  </div>

  <!-- Card 3 -->
  <div class="card" style="flex: 1 1 calc(33% - 1em); box-shadow: 0 0 5px rgba(0,0,0,0.1); border-radius: 8px; overflow: hidden; background: #fff; padding: 1em;">
    <img src="/assets/images/NSCH1200X630.jpg" alt="NSCH thumbnail" style="width: 100%; border-radius: 6px;">
    <h4>National Survey of Children's Health - Branding Video</h4>
    <p>Designed this video to raise awareness of this survey, strengthen public trust in the agency behind it, and encourage participation from parents and caregivers.</p>
    <p><a href="#">Watch video</a></p>
  </div>

  <!-- Card 4 -->
  <div class="card" style="flex: 1 1 calc(33% - 1em); box-shadow: 0 0 5px rgba(0,0,0,0.1); border-radius: 8px; overflow: hidden; background: #fff; padding: 1em;">
    <img src="/assets/images/F2F1200X630.jpg" alt="Family's Journey thumbnail" style="width: 100%; border-radius: 6px;">
    <h4><em>A Family’s Journey</em> – Systems Change Storytelling</h4>
    <p>Follow one family’s experience navigating complex medical, educational, and social challenges, and the critical support they received from their "F2F" center. I wrote this narrative for Congressional decision-makers and for support centers to tell their story.</p>
    <p><a href="#">Read the story</a></p>
  </div>

  <!-- Card 5 -->
  <div class="card" style="flex: 1 1 calc(33% - 1em); box-shadow: 0 0 5px rgba(0,0,0,0.1); border-radius: 8px; overflow: hidden; background: #fff; padding: 1em;">
    <img src="/assets/images/Clapperboard1200X630.jpg" alt="Film clapperboard thumbnail" style="width: 100%; border-radius: 6px;">
    <h4>Evacuation Plan – Film Set / Same‑Day Delivery</h4>
    <p>This comprehensive evacuation plan - for a high-profile production filming on location - is tailored to the specific geography and personnel needs of 500 crew and extras. I used AI tools to cut concept-to-delivery time by an estimated 70%, enabling same-day turnaround.</p>
    <p><em>Details available upon request.</em></p>
  </div>

  <!-- Card 6 -->
  <div class="card" style="flex: 1 1 calc(33% - 1em); box-shadow: 0 0 5px rgba(0,0,0,0.1); border-radius: 8px; overflow: hidden; background: #fff; padding: 1em;">
    <img src="/assets/images/Cruiseship1200X630.jpg" alt="Cruise ship thumbnail" style="width: 100%; border-radius: 6px;">
    <h4>Marketing Package – Alaska Tourism Pitch / Cruise Outreach</h4>
    <p>This marketing package (proposal, cover letter, press release) is for a small recreation and entertainment business in Alaska. They successfully secured cruise rep engagement. Used AI tools for research, drafting, and image generation under a tight deadline.</p>
    <p><em>Details available upon request.</em></p>
  </div>

</div>

</section>




<!-- Training -->
<section id="training">
  <h2>Training</h2>

  <p>Need help getting practical in this evolving AI landscape? Struggle with helping your teams to write clearly and effectively? Looking for someone to help enable your nontechnical teams to use AI tools and understand what they can and can’t quite do?</p>

  <p>I can help! Feel free to get in touch. 📬 <a href="mailto:forwardstory@gmail.com">forwardstory@gmail.com</a></p>

  <details class="expander" id="training-expander">
    <summary>See training offerings <span class="plus" aria-hidden="true">+</span></summary>

    <ul class="training-list">
      <li>
        <strong>🟣 Write It Clearly: Training for Teams (with AI-Enhanced Support)</strong> — Helps teams write clearly and confidently — with or without AI tools. You’ll learn how to turn complex ideas into accessible, actionable content, and how to use GenAI to support your process, not replace it.
      </li>
      <li>
        <strong>🟣 Storytelling: Craft Messages That Stick, Scale, and Inspire</strong> — Helps teams and individuals bring their mission, products, or services to life with compelling, structured stories. You’ll learn how to connect messaging to audience needs, organize your ideas for clarity and flow, and use GenAI to prototype content quickly — without losing your voice. Whether you're building a brand, launching a campaign, or briefing leadership, the right story drives understanding and engagement.
      </li>
      <li>
        <strong>🟣 AI-Literacy for Nontechnical Teams: Be the Human in the Loop</strong> — Plain-language overview of generative AI, what it’s good at (and not), and how to use it thoughtfully in daily work. You’ll walk away with a practical, no-hype understanding of where these tools fit in your work.
      </li>
    </ul>
  </details>
</section>


<!-- Contact -->
<section id="contact">
<h2>Contact</h2>
<p>📍 Wherever there is wifi | Reach out if you'd like to collaborate, build clearer content, or explore AI tools for your team:</p>  
<p>📬 <a href="mailto:forwardstory@gmail.com">forwardstory@gmail.com</a></p>
</section>
