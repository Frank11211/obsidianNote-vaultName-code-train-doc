- Edelteq Panasonic:
	- Issue 
		- Panasonic Driver don't have torque when servo on
		- RSI prompt issue on AMP Active late 500ms
		
	- Suspect 
		- Panasonic XML got issue, 
		- InTime kernel there too short for respond (50ms in InTime config)
		  
	- Action 
		- 2pm try again, because customer wiring Panasonic Driver
		- Panasonic Vendor pass another XML to CH, retry again. 
		- Check with Ideal Vision, see they need additional do any Panasonic setting 
			- **No Need** do any additional setting
			- Possible, get their RSI NodeInfo + XML 
		
	- Conclusion 
		- Wait and continue do on 2pm
	
- Greatech 
	- Issue 
		- Need schedule a time to  visit Greatech + explain to them how our sample program work 
	- Action 
		- Show + explain to them on what you had write in Q-program , they had setup hardware for us
	- Conclusion 
		- Customer acknowledge about it, and will let them konw further


- Internal task
	- Penta - Setup RSI
		- Action 
			- require to check and ensure RSI able to work before demo
	- ABS encoder -Fuji 
		- Loan out the supported motor model , test on the endless loop for Koay
		