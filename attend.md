---
layout: default
title: Attend
permalink: /attend/
hero-image: 
  webp: /assets/hero-attend.webp
  fallback: /assets/hero-attend.png
---

<div class="alert alert-info">
<strong>Welcome to the great outdoors, furry style! Whether you're new to the woods or a seasoned camper, F.L.A.W. offers a fun, safe, and unforgettable weekend surrounded by nature and great company. Come make memories under the stars!</strong>
</div>

## Registration

<div class="alert alert-danger">
<h4>Registration for F.L.A.W. 2026 <span id=countdown>will be closing Monday, May 18th!</span></h4>
</div>

<picture>
<source type="image/webp" srcset="/assets/regdog.webp">
<img src="/assets/regdog.png" alt="F.L.A.W. Registration Mascot" class="float-end ms-3 mb-3" style="max-height: 220px;">
</picture>

All registrations are processed through [ConCat](https://www.concat.app/) and paid via Stripe.

<div id="reg-button" class="my-3">
    <a href="https://reg.campflaw.org/" class="btn btn-success btn-lg" style="color: #fff !important;">Registration Portal</a>
</div>

<script>let closeDate=new Date("May 18, 2026 23:59:59 EST").getTime(),countdown=document.querySelector("#countdown"),updateTime=()=>{now=Date.now(),diff=closeDate-now;let e=Math.floor(diff/864e5),o=Math.floor(diff%864e5/36e5),n=Math.floor(diff%36e5/6e4);e+o+n>0?countdown.innerHTML=`will be closing on Monday, May 18th (in ${e} days, ${o} hours, and ${n} ${1==n?"minute":"minutes"})!`:countdown.innerText="Registration for F.L.A.W. 2026 is now closed! Day passess will be available on-site."};updateTime(),setInterval(updateTime,6e4);</script>

## Registration Types

<div class="row row-cols-1 row-cols-md-3 g-4 my-3">
    <div class="col">
        <div class="card h-100 shadow-sm">
            <div class="card-body">
                <h4 class="card-title fw-bold" style="color: #234c41;">Camper <span class="badge bg-secondary">$175</span></h4>
                <p class="text-muted">The original experience!</p>
                <ul>
                    <li>Full weekend admission</li>
                    <li>Cabin bunk assignment</li>
                    <li>6 meals included</li>
                    <li>Access to all activities and programming</li>
                </ul>
            </div>
        </div>
    </div>
    <div class="col">
        <div class="card h-100 shadow-sm">
            <div class="card-body">
                <h4 class="card-title fw-bold" style="color: #234c41;">Survivalist <span class="badge bg-secondary">$250</span></h4>
                <p class="text-muted">Go above and beyond to support F.L.A.W.</p>
                <ul>
                    <li>Everything in Camper</li>
                    <li>Included t-shirt</li>
                    <li>Special token of our appreciation</li>
                    <li>Support the event and future growth</li>
                </ul>
            </div>
        </div>
    </div>
    <div class="col">
        <div class="card h-100 shadow-sm">
            <div class="card-body">
                <h4 class="card-title fw-bold" style="color: #234c41;">Trailblazer <span class="badge bg-secondary">$325</span></h4>
                <p class="text-muted">The elevated glamping experience.</p>
                <ul>
                    <li>All items from previous tiers</li>
                    <li>Placement in exclusive premium cabin with full furnishing, bedding, water, and electricity</li>
                    <li>F.L.A.W. flask and mug</li>
                    <li>2 special gifts disclosed onsite</li>
                    <li>Custom badge of your sona drawn by our art department</li>
                </ul>
            </div>
        </div>
    </div>
</div>

<div class="row row-cols-1 row-cols-md-2 g-4 my-2">
    <div class="col">
        <div class="card h-100 shadow-sm border-secondary">
            <div class="card-body">
                <h5 class="card-title fw-bold">Day Badge <span class="badge bg-secondary">At-Con Only</span></h5>
                <p class="text-muted mb-0">Purchased on-site only. Single-day admission with access to activities and programming. Meals not included.</p>
            </div>
        </div>
    </div>
    <div class="col">
        <div class="card h-100 shadow-sm border-secondary">
            <div class="card-body">
                <h5 class="card-title fw-bold">Minor Policy <span class="badge bg-warning"><i class="bi bi-exclamation-triangle-fill px-2"></i></span></h5>
                <p class="text-muted mb-1">Finger Lakes Anthro Weekend is an all-ages event! For attendees under the age of 18, a few restrictions apply:</p>
                <ul class="small mb-0">
                    <li>Ages 0&ndash;14 must be accompanied by a parent or legal guardian at all times. The parent/legal guardian must register for the event under <strong>their own account,</strong> using their information not the child's.</li>
                    <li>Ages 15&ndash;17 can attend with notarized permission from a parent or legal guardian</li>
                    <li>Guardians assume full responsibility for minors</li>
                </ul>
            </div>
        </div>
    </div>
</div>

## Capacity

Attendance is capped at **100**.
