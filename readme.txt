1 The demo test on the small net
(1) data description
  node.csv: node_id
  link.csv: from_node, to_node, FreeFlowTravelTime, capacity, apher, power
  od.csv: origin, destination, demand

(2) run code
  click TP_solve_small.exe

(3) store the output data in text
  open the cmd.exe in the folder, then input "TP_solve_small.exe > TP_solve_small_result_temp.log"

2 Test data sources (Anaheim, Chicago Sketch, Birmingham-England and Philadelphia network) can be obtained from  https://github.com/bstabler/TransportationNetworks.


