# cargo-expert
trans Goods
package main

import (
	"fmt"
)



func main() {
	var (
		p= 1234
		user= "jamal"
		amount int
		pin = 1820

		 input int
		phonenumber  int
		location string

		cargoname string
		cargokilogram string

	)
	fmt.Println("Enter your name")
	fmt.Scanln(&user)

	if user != "jamal" {
		fmt.Println("wrong user name")
	} else {

		fmt.Println("Enter your pin")
		fmt.Scanln(&p)

		if p == 1234 {
			fmt.Println("Welcome CargoExpert")
			fmt.Println("Choose Your Transporter (LOCATED)(UNLOCKED)")

			fmt.Println("1: JOHN JACKSON")
			fmt.Println("2: ALLY MICHAEL")
			fmt.Println("3: JOSEPH GEORGE")
			fmt.Println("4: BAK HENRY")
			fmt.Println("5: JORDAN MIKE")
			fmt.Scanln(&input)
			switch (input) {
			case 1:
				fmt.Println("This is me |JOHN JACKSON| cargo expert transporter am here to listen you!!")
				fmt.Println("Please Enter your Cargo Information ..")
				fmt.Println("Enter Your Location Identified By Street/Home Address/etc..")
				fmt.Scanln(&location)
				fmt.Println("Enter Cargo name ")
				fmt.Scanln(&cargoname)
				fmt.Println("Enter Cargo Kilogram")
				fmt.Scanln(&cargokilogram)
				fmt.Println("Enter Your Phone Number")
				fmt.Scanln(&phonenumber)

				fmt.Println("After Few Mints I will catch You.")

				fmt.Println("Thanks for Trust Me Your Welcome Again,  Am on My Way.. ")

			case 2:
				fmt.Println("This is me <ALLY MICHAEL> cargo expert transporter am here to listen you!!")
				fmt.Println("Please Enter your Cargo Information ..")
				fmt.Println("Enter Your Location Identified By Street/Home Address/etc..")
				fmt.Scanln(&location)
				fmt.Println("Enter Cargo name ")
				fmt.Scanln(&cargoname)
				fmt.Println("Enter Cargo Kilogram")
				fmt.Scanln(&cargokilogram)
				fmt.Println("Enter Your Phone Number")
				fmt.Scanln(&phonenumber)

				fmt.Println("After Few Mints I will catch You.")

				fmt.Println("Thanks for Trust Me Your Welcome Again,  Am on My Way.. ")

			case 3:
				fmt.Println("This is me [JOSEPH GEORG] cargo expert transporter am here to listen you!!")
				fmt.Println("Please Enter your Cargo Information ..")
				fmt.Println("Enter Your Location Identified By Street/Home Address/etc..")
				fmt.Scanln(&location)
				fmt.Println("Enter Cargo name ")
				fmt.Scanln(&cargoname)
				fmt.Println("Enter Cargo Kilogram")
				fmt.Scanln(&cargokilogram)
				fmt.Println("Enter Your Phone Number")
				fmt.Scanln(&phonenumber)

				fmt.Println("After Few Mints I will catch You.")

				fmt.Println("Thanks for Trust Me Your Welcome Again,  Am on My Way.. ")

			case 4:
				fmt.Println("This is me {BAK HENRY} cargo expert transporter am here to listen you!!")
				fmt.Println("Please Enter your Cargo Information ..")
				fmt.Println("Enter Your Location Identified By Street/Home Address/etc..")
				fmt.Scanln(&location)
				fmt.Println("Enter Cargo name ")
				fmt.Scanln(&cargoname)
				fmt.Println("Enter Cargo Kilogram")
				fmt.Scanln(&cargokilogram)
				fmt.Println("Enter Your Phone Number")
				fmt.Scanln(&phonenumber)

				fmt.Println("After Few Mints I will catch You.")

				fmt.Println("Thanks for Trust Me Your Welcome Again,  Am on My Way.. ")

			case 5:
				fmt.Println("This is me (JORDAN MIKE) cargo expert transporter am here to listen you!!")
				fmt.Println("Please Enter your Cargo Information ..")
				fmt.Println("Enter Your Location Identified By Street/Home Address/etc..")
				fmt.Scanln(&location)
				fmt.Println("Enter Cargo name ")
				fmt.Scanln(&cargoname)
				fmt.Println("Enter Cargo Kilogram")
				fmt.Scanln(&cargokilogram)
				fmt.Println("Enter Your Phone Number")
				fmt.Scanln(&phonenumber)

				fmt.Println("After Few Mints I will catch You.")

				fmt.Println("Thanks for Trust Me Your Welcome Again,  Am on My Way.. ")
				fmt.Println(" 1: Press one for Track your Cargo")
				fmt.Println("2: give us some donation ")

				 fmt.Scanln(&input)

				switch (input) {
				case 1:
					fmt.Println("Your Cargo is in road number 676 1 kilometre to destination Location ")
				case 2:
					fmt.Println("Choose Your Mobile Network")
					fmt.Println(" 1: Vodacom Tanzania")
					fmt.Println("2: Airtel Tanzania")
					fmt.Println("3: Halotel Tanzani")
					fmt.Println("4: TTCL Coparation")
					fmt.Println("....")
					fmt.Scanln(&input)

					switch (input) {
					case 1:
						fmt.Println("Enter your vodacom Number . . .")
						fmt.Scanln(&phonenumber)
						fmt.Println("Enter Your Amount . . .")
						fmt.Scanln(&amount)
						fmt.Scanln("Enter M-pesa password . . .")
						fmt.Scanln(&pin)

					case 2:
						fmt.Println("Enter your Airtel Number . . .")
						fmt.Scanln(&phonenumber)
						fmt.Println("Enter Your Amount . . .")
						fmt.Scanln(&amount)
						fmt.Scanln("Enter Airtel money password . . .")
						fmt.Scanln(&pin)

					case 3:
						fmt.Println("Enter your halotel Number . . .")
						fmt.Scanln(&phonenumber)
						fmt.Println("Enter Your Amount . . .")
						fmt.Scanln(&amount)
						fmt.Scanln("Enter Halopesa password . . .")
						fmt.Scanln(&pin)

					case 4:
						fmt.Println("Enter your ttcl Number . . .")
						fmt.Scanln(&phonenumber)
						fmt.Println("Enter Your Amount . . .")
						fmt.Scanln(&amount)
						fmt.Scanln("Enter TTCL pesa password . . .")
						fmt.Scanln(&pin)

					}



				}




			}



		} else {
			fmt.Println("try again..")
		}

	}
}
