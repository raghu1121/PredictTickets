# PredictTickets
__A model that  predicts how many tickets will be sold and finds optimal prices for those tickets.__

Description of the data:

- `index`: unique identifier for the bus ride
- `ride_departure`: departure date and time of the ride
- `capacity`: number of total seats available in the bus
- `tickets_{X}_eur`: number of tickets sold for `X` Euro
- `direction`: direction of the bus ride, either A->B or B->A

__This model predicts with a MAE of 4 tickets.__
