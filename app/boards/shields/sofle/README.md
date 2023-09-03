Build Left Side:
zmk@zmk-Virtual-Machine:~/github/zmk/app$ west build --pristine -b nice_nano_v2 -- -DSHIELD="sofle_left nice_view_adapter nice_view"

Build Right Side:
zmk@zmk-Virtual-Machine:~/github/zmk/app$ west build --pristine -b nice_nano_v2 -- -DSHIELD="sofle_right nice_view_adapter nice_view"

Files output to:
/home/github/zmk/app/build/zephyr/zmk.uf2