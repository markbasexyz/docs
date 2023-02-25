- Log into [[stripe]]
- Navigate to [[stripe-page-customers]]
- Filter for [[email]]
- Select email 
- You are on [[customer-page]] 
- Copy [[stripeId]] under "Details" section (ex: `cus_Ll52AQwMon5gKe`)
- Log into [[public/markbase/Garage/dictionary/supabase]]
- Ensure you are in markbaseteam's Org
- Select [[[markbasepostgres]]]
- Select Database
- Select [[table-user]]
- Filter by [[stripeId]]
- Paste stripeId copied to clipboard from Stripe
- Copy [[id-varchar]] to clipboard
- Navigate to [[table-project]]
- Filter by [[userId]]
- Paste [[id-varchar]] copied to clipboard from [[table-user]]
	- NOTE: [[id-varchar]] from [[table-user]] == [[userId]] from [[table-project]]
- For project details refer to [[publishedUrl]]
- You have successfully checked user project based on email


backlinks: [[stripe]] [[public/markbase/Garage/dictionary/supabase]]
tags: 

