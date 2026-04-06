---
layout: university_page
title: University of British Columbia
short-title: UBC
landing-title: " "
description: IOB AT UNIVERSITY OF BRITISH COLUMBIA
image: assets/images/pic13.jpg
author: null
tag: home
weight: 1
---

<!-- Main -->

{% include header.html %}

  <section id="banner" class="banner-sponsor">
    <div class="inner">
      <header class="major">
        <h1>{{ page.title }}</h1>
      </header>
      <p>
       Innovation OnBoard is a student-led entrepreneurship program featuring bi-weekly seminars and workshops, culminating in a premier venture competition where teams compete for cash prizes. We foster innovation by providing a forum to build cohesive, multidisciplinary teams, simplify the entrepreneurial experience, and launch new ventures.
      </p>
      <!-- New line and button layout -->
      <div style="display: flex; align-items: center; gap: 25px; flex-wrap: wrap;">
        <p style="margin: 0; font-weight: bold; text-transform: uppercase; letter-spacing: 1px; font-size: 18px;">
          Next Up: We're Hiring for Executive Positions
        </p>
        <ul class="actions" style="margin: 0; padding: 0; list-style: none;">
          <li style="padding: 0; margin: 8px 0 0 0;"> 
            <a href="https://docs.google.com/forms/d/e/1FAIpQLSe2Q-T7t88xZXe7mXDa8LnnDqYo7TE4__0Fgxk7rqGmDta5Jw/viewform" 
              target="_blank" 
              rel="noopener noreferrer" 
              class="button fit" 
              style="color: white; background-color: transparent; transition: 0.3s; border: 1px solid white;"
              onmouseover="this.style.color='white'; this.style.backgroundColor='#002047'; this.style.borderColor='#002047';" 
              onmouseout="this.style.color='white'; this.style.backgroundColor='transparent'; this.style.borderColor='white';">
              Apply Now
            </a>
          </li>
        </ul>
      </div>
    </div>
  </section>
<div id="main" class="alt">
    <section id="one" class="alt">
      <div class="inner">
        <header>
          <div class="row">
            <div class="6u 12u$(small)">
              <div class="box">
                <h1>Workshops Sign Up</h1>
                <p>
                  Unlock the path to entrepreneurship, connect with fellow startup enthusiasts, and gain valuable
                  insights from experienced entrepreneurs and industry experts. Sign up to receive event reminders.
                </p>
                <!-- <ul class="actions fit">
                  <li>
                    <a href="http://localhost:4000/participant-signup.html" target="_blank" class="button fit">Sign Up</a>
                  </li>
                </ul> -->
                <ul class="actions fit">
                  <li>
                    <a href="https://www.eventbrite.ca/o/innovation-onboard-34101770019" target="_blank" rel="noopener noreferrer" class="button fit">Sign Up</a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="6u 12u$(small)">
              <div class="box">
                <h1>Stay Connected</h1>
                <p> 
                  Join our community to stay in the loop! Sign up for our newsletter for event news, 
                  and join our Discord to collaborate with fellow innovators and find your next teammate.
                </p>
                <br />
                <ul class="actions fit">
                  <li>
              <a href="{{ '/signup.html' | prepend: site.baseurl | prepend: site.url }}"
                      target="_blank" class="button fit">Newsletter Sign Up</a>
                  </li>
                  <li>
              <a href="https://discord.gg/Y95GrgqcCS" target="_blank" rel="noopener noreferrer" class="button fit" style="color: white; background-color:#002047">Discord</a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="6u 12u$(small)">
              <div class="box">
                <h1>Innovation Fair</h1>
                <p>
                  A high-energy showcase where student founders present their startups and prototypes to industry experts and the public.
                </p>
                <p>
                  <i>Note: Team applications for the Innovation Fair are currently closed and will reopen in October.</i>
                </p>
                <!-- <ul class="actions fit">
                  <li>
                    <a href="http://localhost:4000/participant-signup.html" target="_blank" class="button fit">Sign Up</a>
                  </li>
                </ul> -->
              </div>
            </div>
            <div class="6u 12u$(small)">
              <div class="box">
                <h1>Join the IOB Team</h1>
                <p> Looking to get involved in an exciting project? Apply now, and we’ll reach out to you via email. Joining IOB is a fantastic opportunity to build valuable experience. 
                </p>
                <p>
                  <i>Note: Applications to join the Innovation OnBoard executive team are currently closed. We will be reopening applications soon!</i>
                </p>
                <!-- <ul class="actions fit">
                  <li>
              <a href="http://localhost:4000/job-posting" class="button fit" style="color: white; background-color:#002047">Apply Here</a>
                  </li>
                </ul> -->
              </div>
            </div>
          </div>
        </header>
      </div>
    </section>
</div>

{% include tiles.html page="ubc" %}
