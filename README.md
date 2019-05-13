.form
	form(action="/" method="POST") 
		.back 
			span
				i(class="fa fa-arrow-circle-left" aria-hidden="true")
		h3
			| Enter your credentials
		.inputs 
			.email
				input.first(type="text" placeholder="Your email")
				button.next
					| Next
			.password
				input.second(type="password" placeholder="Enter Password")
				button.login
					| Log in

p.warning

	
