# zipToCounty
Quick and dirty webpage that fills in city, state, and county after entering zip code. Inspired by Stephanie Weatherford...

There are many existing city and state fill-in forms; not many that pull county.

Google has a 'Geocoding' API that has what is called 'administrative_area_level_2.' This is a field that corresponds to 'County' in most of the USA.

The HTML is horrible -- I know! This is more a proof of concept webapp to work with APIs...I needed the practice (still do). The code itself is very buggy. Also, it appears that not every zip code is mapped to a specific county within this API. You still get the city for most of these and will have to do a generic Google search for the County for that city.

I looked at many good code examples, not the least of which were Googles geocoding examples. Also I got a lot from https://github.com/kovalent/examples and https://github.com/ekotechnology/Zippopotamus-Cloud -- go check out their work.

My webapp is basically a combination of what these guys have done with the addition of combing through Google's very extensive documentation to find 'administrative_area_level_2.'
