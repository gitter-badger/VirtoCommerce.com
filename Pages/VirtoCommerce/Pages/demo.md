---
layout: post
title: Enterprise .net open-source ecommerce cloud platform. Demo
description: Enterprise .net open-source ecommerce cloud platform. Demo
date: 2014-01-30
permalink: /pages/demo
tags : 
- demo
- commerce
---
<article role="main" class="main">
	<div class="partner __responsive">
		<h1 class="head-title">Personal Demo</h1>
		<p class="text">Tell us about your project and requirements and we’ll organize a personalized walk-through of Virto Commerce for you and your colleagues in ways to best address your needs.</p>
		<div class="columns">
			<div class="column">
				<div class="block">
					<form class="fixed" action="">
						<input type="hidden" value="Signup for Personal Demo" name="Subject" />
						<input type="hidden" value="true" name="IsResend" />
						<input type="hidden" value="/thank-you-demo" name="RedirectUrl" />
						<div class="control-group">
							<label for="fullName">Full name</label>
							<input type="text" name="FullName" class="form-input" required>
						</div>
						<div class="control-group">
							<label for="email">Email</label>
							<input type="text" name="To" class="form-input">
						</div>
						<div class="control-group">
							<label for="email">Company name</label>
							<input type="text" name="CompanyName" class="form-input" required>
						</div>
						<div class="control-group">
							<label for="company">Number of Employees</label>
							<select type="text" name="NumberOfEmployees" class="form-input" required>
								<option value="">Select Option</option>
								<option value="1">Less than 10</option>
								<option value="11">10 to 100</option>
								<option value="101">101 to 300</option>
								<option value="301">301 to 500</option>
								<option value="501">501 to 1000</option>
								<option value="1001">1000 or more</option>
							</select>
						</div>
						<div class="control-group">
							<label for="web">Company total annual revenue</label>
							<select type="text" name="CompanyTotalAnnualRevenue" class="form-input" required>
								<option value="">Select Option</option>
								<option value="1k">Less than $500K</option>
								<option value="501k">$500K - $1M</option>
								<option value="1001k">$1M - $10M</option>
								<option value="10001k">$10M - $25M</option>
								<option value="25001k">$25M - $50M</option>
								<option value="50001k">$50M - $100M</option>
								<option value="100001k">$100M - $500M</option>
								<option value="500001k">Greater than $500M<</option>
							</select>
						</div>
						<div class="control-group">
							<label for="descr">Comments</label>
							<textarea rows="10" cols="30" name="Comments" class="form-text" required></textarea>
						</div>
						<div class="control-group">
							<button class="button fill" type="submit">Send Request</button>
						</div>
					</form>
				</div>
			</div>
		</div>
	</div>
	{% include technologies.html %}
</article>
