# Information panel with remote weather station - live monitoring of temperature, humidity, barometric pressure, air pollution, wind speeda nd direction

This project will allow user to monitor the weather as well as news
and  calendar information at the glance. Project will consist of two
wirelessly connected stations.

Information panel will be configured to turn on between chosen hours
and on demand. Using a low powered computer connected to the TV with
CEC  auto power on, power usage will be very low.
The remote Weather station will use an ESP32 microcontroller as
it  can take advantage of the sleep mode making the power usage as low
as  possible.

Weather station will be powered from a battery pack. That battery
pack  might also use solar panels as additional power to help it last
as long  as possible on single charge.
If the weather station will be efficient enough, the only service
required will be to clean the solar panels once in a while.
When power stored in the battery pack will drop below 25%, user will
be  notified about it on the Information panel.
Weather station will use sensors to gather information from the
surroundings and send them to the Information panel.
After transferring the data to the Information panel, Weather
station  will turn into the low powered mode until next read out.
Frequency of the read out will be configurable by the user, but less
frequent read outs will result in lower power usage and longer life
without servicing.
Weather station will have to be weather proof and unintrusive to the
surrounding nature, that's why my goal is to disguise it as a bird
house.
Lower part will contain the microcontroller with temperature and
humidity sensors and on the top of the bird house there will be an
anemometer and solar panels to receive the most sunlight.
