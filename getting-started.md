---
layout: form
title: Getting Started
---
# Getting Started

In order to get started, first fill out the form below to contact us and have us set up a private instance of the software just for you.   Your private instance allows you to upload you code safely in a way that only you will be able to access it.

Once you have filled out and submitted the contact form below, we will set up an instance of the software and contact you with a unique private URL that you can use to access it.  Then, you can set up an account and begin to analyse your software code.

<br />

<form>
	<div class="form-group">
		<label>First name</label>
		<div class="input-group">
			<input type="text" class="form-control" />
			<div class="input-group-append">
				<span class="input-group-text">
					<i class="active fa fa-question-circle" data-toggle="popover" data-placement="top" data-container="body" title="First name" data-content="This is the informal name or given name that you are called by."></i>
				</span>
			</div>
		</div>
	</div>
	<div class="form-group">
		<label>Last name</label>
		<div class="input-group">
			<input type="text" class="form-control" />
			<div class="input-group-append">
				<span class="input-group-text">
					<i class="active fa fa-question-circle" data-toggle="popover" data-placement="top" data-container="body" title="Last name" data-content="This is your family name."></i>
				</span>
			</div>
		</div>
	</div>
	<div class="form-group">
		<label>Affiliation</label>
		<div class="input-group">
			<input type="text" class="form-control" />
			<div class="input-group-append">
				<span class="input-group-text">
					<i class="active fa fa-question-circle" data-toggle="popover" data-placement="top" data-container="body" title="Affiliation" data-content="This is the organization that you are affiliated with."></i>
				</span>
			</div>
		</div>
	</div>
	<div class="form-group">
		<label>Email</label>
		<div class="input-group">
			<input type="text" class="form-control" />
			<div class="input-group-append">
				<span class="input-group-text">
					<i class="active fa fa-question-circle" data-toggle="popover" data-placement="top" data-container="body" title="Email" data-content="This is your email address so we can notify you when your instance is ready to use."></i>
				</span>
			</div>
		</div>
	</div>
	<div>
		<label>Programming Languages</label>
		{% for item in site.data.languages %}
		<div class="form-check">
			<input class="form-check-input" type="checkbox">
			<label class="form-check-label">{{ item.name }}</label>
		</div>
		{% endfor %}
	</div>

</form>

<br />

<div class="buttons">
	<button id="submit" class="btn btn-primary btn-lg"><i class="fa fa-envelope"></i>Submit</button>
</div>
