# Quiz_887342
# Hello World Program in Ruby
puts "Hello World!";
US_states = 

	{"Alabama" => "AL",
	"Alaska" => "AK",
	"Arizona" => "AZ",
	"Arkansas" => "AR",
	"California" => "CA",
	"Colorado" => "CO",
	"Connecticut" => "CT",
	"Delaware" => "DE",
	"District of Columbia" => "DC",
	"Florida" => "FL",
	"Georgia" => "GA",
	"Hawaii" => "HI",
	"Idaho" => "ID",
	"Illinois" => "IL",
	"Indiana" => "IN",
	"Iowa" => "IA",
	"Kansas" => "KS",
	"Kentucky" => "KY",
	"Louisiana" => "LA",
	"Maine" => "ME",
	"Maryland" => "MD",
	"Massachusetts" => "MA",
	"Michigan" => "MI",
	"Minnesota" => "MN",
	"Mississippi" => "MS",
	"Missouri" => "MO",
	"Montana" => "MT",
	"Nebraska" => "NE",
	"Nevada" => "NV",
	"New Hampshire" => "NH",
	"New Jersey" => "NJ",
	"New Mexico" => "NM",
	"New York" => "NY",
	"North Carolina" => "NC",
	"North Dakota" => "ND",
	"Ohio" => "OH",
	"Oklahoma" => "OK",
	"Oregon" => "OR",
	"Pennsylvania" => "PA",
	"Rhode Island" => "RI",
	"South Carolina" => "SC",
	"South Dakota" => "SD",
	"Tennessee" => "TN",
	"Texas" => "TX",
	"Utah" => "UT",
	"Vermont" => "VT",
	"Virginia" => "VA",
	"Washington" => "WA",
	"West Virginia" => "WV",
	"Wisconsin" => "WI",
	"Wyoming" => "WY"}
	puts "- - - - - - - - -1.1 - - - - - - - - - - - - "
	US_states.each {|x,y|
	    if y[1]=="T" ||  y[1]=="N"
	puts y
	end
	}
	puts "- - - - - - - - -1.2 - - - - - - - - - - - - "
    puts US_states.sort.reverse
    
    
    puts "- - - - - - - - -1.3 - - - - - - - - - - - - "
	US_states.each {|x,y|
	if (x[0]=="A"|| x[0]=="E"|| x[0]=="I"|| x[0]=="O"|| x[0]=="U")&&(x[x.length-1]=="a"||x[x.length-1]=="e"||x[x.length-1]=="i"||x[x.length-1]=="o"||x[x.length-1]=="u")
	    puts x
	end
	}
	puts "- - - - - - - - - 2 - - - - - - - - - - - - "
	ทำข้อ2ไม่ได้ครับ 
