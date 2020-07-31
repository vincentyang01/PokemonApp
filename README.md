README
This CLI App was made as the Mod 1 Final Project for the Flatiron Boocamp Software Engineer course.

To install, clone the repo, and 'bundle install' in order to resolve dependencies. Migrate the database with 'rake db:migrate' and seed the data with 'rake db:seed'. Start up the application by running 'ruby tools/run.rb'. Once you have completed the previous steps, you will be Introduced to Professor Oak. He will inform you about whatever you need to know and guide you on this new jouney you are embarking. Good luck and Catch em all!

This a Pokemon app made with data from a JSON file of Generation 1 Pokemon. It is written in Ruby and allows users to view, find/filter, and compare the users Pokemon. You can also release Pokemon from the Pokedex and delete Pokemon and find/filter all Pokemon in the region.

In this program, we have a many to many, through relationship and three relational databases. Access a Sqlite3 Database using ActiveRecord.The indivudal instances of Pokemon serves as our joiners for our two other classes, trainer and Pokemon species. As a result, Trainers has many Pokemon species and Pokemon_species has many trainers, through the instances join table. We create these relationships through accessing Sqlite3 databases using ActiveRecord.



quu..__
 $$$b  `---.__
  "$$b        `--.                          ___.---uuudP
   `$$b           `.__.------.__     __.---'      $$$$"              .
     "$b          -'            `-.-'            $$$"              .'|
       ".                                       d$"             _.'  |
         `.   /                              ..."             .'     |
           `./                           ..::-'            _.'       |
            /                         .:::-'            .-'         .'
           :                          ::''\          _.'            |
          .' .-.             .-.           `.      .'               |
          : /'$$|           .@"$\           `.   .'              _.-'
         .'|$u$$|          |$$,$$|           |  <            _.-'
         | `:$$:'          :$$$$$:           `.  `.       .-'
         :                  `"--'             |    `-.     \
        :##.       ==             .###.       `.      `.    `\
        |##:                      :###:        |        >     >
        |#'     `..'`..'          `###'        x:      /     /
         \                                   xXX|     /    ./
          \                                xXXX'|    /   ./
          /`-.                                  `.  /   /
         :    `-  ...........,                   | /  .'
         |         ``:::::::'       .            |<    `.
         |             ```          |           x| \ `.:``.
         |                         .'    /'   xXX|  `:`M`M':.
         |    |                    ;    /:' xXXX'|  -'MMMMM:'
         `.  .'                   :    /:'       |-'MMMM.-'
          |  |                   .'   /'        .'MMM.-'
          `'`'                   :  ,'          |MMM<
            |                     `'            |tbap\
             \                                  :MM.-'
              \                 |              .''
               \.               `.            /
                /     .:::::::.. :           /
               |     .:::::::::::`.         /
               |   .:::------------\       /
              /   .''               >::'  /
              `',:                 :    .'
                                   `:.:'
