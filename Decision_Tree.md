left: (infoavail, 3)
    left: (policetrust, 2)
        left: (streetquality, 2)
            left: (infoavail, 5)
                left: (schoolquality, 2)
                    left: (policetrust, 5)
                        left: (schoolquality, 3)True
                        right: True
                    right: 
                        left: (schoolquality, 5)
                        False
                        right: True
                right: False
            right: 
                left: (policetrust, 3)
                left: (schoolquality, 5)
                False
                right: 
                    left: (streetquality, 5)True
                    right: False
                right: False
        right: False
    right: True
right: False