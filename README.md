class Character():

    #this sets up the variables in the object
    def __init_(self):
        self.name=""
        self.sex=""
        self.max_hit_point=""
        self.current_hit_points=""
        self.armor_amount=""

    main_char = Character()
    main_char.name = "Max"
    main_char.sex = "Male"
    main_char.max_hit_points = 50
    main_char.max_current_hit_points = 50
    main_char.armor_amount = 8

    print("The main character of the game is", main_char.name)
    print("The maximum amount of hit points is", main_char.max_hit_points)

    class Address()
    def __init_(self):
        self.name = ""
        self.line1 = ""
        self.line2 = ""
        self.city = ""
        self.state = ""
        self.zip = ""

        home_address = Address()
        home_address.name = 'John Smith'
        home_address.line1 = '102 North Street'
        home_address.line2 = 'Carver CS Building'
        home_address.city = 'New York City'
        home_address.state = 'NY'
        home_address.zip = '10010'

        vacation_home_address = Address()
        vacation_home_address.name = 'John Smith'
        vacation_home_address.line1 = '102 South Beach Boulevard'
        vacation_home_address.line2 = 'Apartment 6'
        vacation_home_address.city = 'Miami Beach'
        vacation_home_address.state = 'FL'
        vacation_home_address.zip = '34002'

        print("My vacatuib address is in", vacation_home_address.city)

        rental_home = vacation_home_address
        rental_home.city = "San Francisco"
        rental_home.state = "CA"
        rental_home.zip = "20001"
        print("My rental house is in", rental_home.city)

        
