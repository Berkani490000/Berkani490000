dodge_left():
        turn_left()
        move()
        turn_right()
dodge_right:
        turn_right()
        move()
        turn_left()
while not is_on_target_x(): 										
        while get_x()!=get_target_x():          
                if get_x()<get_target_x():       
                        while get_direction() !=EAST:     
                                        turn_left            
                        if not is_in-front_of_enemy AND can_move():    
                                move()
                              
                        elif get_y>get_target_y: 
                                dodge_left()
                        else:
                                dodge_right()
                else:
                        while get_direction() != WEAST:
                                turn_left()
                        if not is_in_front_of_enemy AND can_move():
                                move()
                        elif not can_move:
                               dodge_left()
                        else: 
                                dodge_right()
        while get_y() != get_target_y():
                if get_y() <get_target_y():
                        while get_direction() != SOUTH:  
                                turn_left()
                        if not is_in_front_of_enemy AND can_move():
                                move()
                        elif get_x <get_target_x :
                                dodge_left()
                        else:   
                        				dodge_right()
                                
                else:
                        while get_direction() !=NORTH:
                                turn_left()
                        if not is_in_front_enemy AND can_move():
                                move()
                        elif not can_move:
                               dodge_left()
                        else:
                               dodge_right()
destroy_target()   

<!---
Berkani490000/Berkani490000 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
