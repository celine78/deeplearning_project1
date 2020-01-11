Modifications used to test the system's robustness:

Colours:

city_people_bike_car_color: magick convert city_people_bike_car.jpg -fuzz 40% -fill brown -opaque green city_people_bike_car_color.jpg

Blurs:

traffic_cars_blurred_0x8: magick convert -blur 0x8 traffic_cars.png traffic_cars_blurred_0x8

crowds-nyc_blurred0x8: magick convert -blur 0x8 crowds-nyc.png crowds-nyc_blurred0x8