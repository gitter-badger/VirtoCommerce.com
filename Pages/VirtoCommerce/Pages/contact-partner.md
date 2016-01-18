---
layout: post
title: Contact our Partners | Virto Commerce Platform
description: Enterprise .NET open-source ecommerce cloud platform. Contact our Partners
date: 2014-01-30
permalink: /pages/contact-partner
---
<article role="main" class="main">
	<div class="roadmap responsive">
		<h1 class="head-title">Contact Partner</h1>
		<p class="text">Use this form to contact partner directly.</p>
		<div class="columns">
			<div class="column">
				<div class="block">
					<form action="">
						<input type="hidden" value="Contact Partner" name="Subject"/>
						<input type="hidden" value="true" name="IsResend"/>
						<input type="hidden" value="/thank-you" name="RedirectUrl" />
						<input type="hidden" value="" name="PartnerId" />
						<div class="control-group">
							<label for="Fullname">Full name:</label>
							<input type="text" class="form-input" name="Fullname" required>
						</div>
						<div class="control-group">
							<label for="To">Email:</label>
							<input type="text" class="form-input" name="To" required>
						</div>
						<div class="control-group">
							<label for="CompanyName">Company name:</label>
							<input type="text" class="form-input" name="CompanyName" required>
						</div>
						<div class="control-group">
							<label for="Kickoff">When do you want to kick off this project?</label>
							<select type="text" name="Kickoff" class="form-input" required>
								<option value="" selected>Select Option</option>
								<option value="immediately">Immediately</option>
								<option value="1-3 months">1-3 months</option>
								<option value="3-6 months">3-6 months</option>
								<option value="6-12 months">6-12 months</option>
								<option value="no timeframe">No timeframe</option>
							</select>
						</div>
						<div class="control-group">
							<label for="descr">Comments</label>
							<textarea rows="10" cols="30" name="Comments" class="form-text" required></textarea>
						</div>
						<div class="control-group">
							<button class="button fill" type="submit">Submit request</button>
						</div>
					</form>
				</div>
			</div>
			<div class="column">
				<div class="block">
					<h3>Frequently asked questions</h3>
					<ul class="list">
						<li>
							<span class="title">When will I get reply from a partner?</span>
							<span class="descr">You should get reply from a partner within a business day. Please be aware of partner timezone. If 
							you don't get any reply within a day, please email us at sales@virtocommerce.com and will make sure you get questions answered.</span>
						</li>
					</ul>
				</div>
			</div>
		</div>
	</div>
	{% include technologies.html %}
</article>
