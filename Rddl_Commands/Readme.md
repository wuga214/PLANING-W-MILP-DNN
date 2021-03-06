Data Generation Commands
===

## Reservoir_4
./run rddl.sim.DomainExplorer -R files/Reservoir/Reservoir_4/Reservoir.rddl -P rddl.policy.domain.reservoir.StochasticReservoirPolicy -I is1 -V rddl.viz.ValueVectorDisplay -K 5000 -D nn/Reservoir/Reservoir_4/Reservoir_Data.txt -L nn/Reservoir/Reservoir_4/Reservoir_Label.txt >log.txt

## Reservoir_3
./run rddl.sim.DomainExplorer -R files/Reservoir/Reservoir_3/Reservoir.rddl -P rddl.policy.domain.reservoir.StochasticReservoirPolicy -I is1 -V rddl.viz.ValueVectorDisplay -K 5000 -D nn/Reservoir/Reservoir_3/Reservoir_Data.txt -L nn/Reservoir/Reservoir_3/Reservoir_Label.txt >log.txt

## HVAC_6
./run rddl.sim.DomainExplorer -R files/HVAC/ROOM_6/HVAC_VAV.rddl2 -P rddl.policy.domain.HVAC.HVACPolicy_VAV -I inst_hvac_vav_fix -V rddl.viz.ValueVectorDisplay -K 5000 -D nn/HVAC/ROOM_6/HVAC_Data.txt -L nn/HVAC/ROOM_6/HVAC_Label.txt

## HVAC_3
./run rddl.sim.DomainExplorer -R files/HVAC/ROOM_3/HVAC_VAV.rddl2 -P rddl.policy.domain.HVAC.HVACPolicy_VAV -I inst_hvac_vav_fix -V rddl.viz.ValueVectorDisplay -K 5000 -D nn/HVAC/ROOM_3/HVAC_Data.txt -L nn/HVAC/ROOM_3/HVAC_Label.txt

## Navigation_8x8
./run rddl.sim.DomainExplorer -R files/Navigation/8x8/Navigation_Radius.rddl -P rddl.policy.domain.navigation.StochasticNavigationPolicy -I is1 -V rddl.viz.ValueVectorDisplay -K 5000 -D nn/Navigation/8x8/Navigation_Data.txt -L nn/Navigation/8x8/Navigation_Label.txt

## Navigation_10x10
./run rddl.sim.DomainExplorer -R files/Navigation/10x10/Navigation_Radius.rddl -P rddl.policy.domain.navigation.StochasticNavigationPolicy -I is1 -V rddl.viz.ValueVectorDisplay -K 5000 -D nn/Navigation/10x10/Navigation_Data.txt -L nn/Navigation/10x10/Navigation_Label.txt


Fixed Policy Performance Extraction
===

## Reservoir_4
./run rddl.sim.DomainExplorer -R files/Reservoir/Reservoir_4/Reservoir.rddl -P rddl.policy.domain.reservoir.FixReservoirPolicy -I is1 -V rddl.viz.ValueVectorDisplay -K 1 -D logs/Reservoir_4_Data.txt -L logs/Reservoir_4_Label.txt

## Reservoir_3
./run rddl.sim.DomainExplorer -R files/Reservoir/Reservoir_3/Reservoir.rddl -P rddl.policy.domain.reservoir.FixReservoirPolicy -I is1 -V rddl.viz.ValueVectorDisplay -K 1 -D logs/Reservoir_3_Data.txt -L logs/Reservoir_3_Label.txt

## HVAC_6
./run rddl.sim.DomainExplorer -R files/HVAC/ROOM_6/HVAC_VAV.rddl2 -P rddl.policy.domain.HVAC.HVACPolicy_VAV_det -I inst_hvac_vav_fix -V rddl.viz.ValueVectorDisplay -K 1 -D logs/HVAC_6_Data.txt -L logs/HVAC_6_Label.txt

## HVAC_3
./run rddl.sim.DomainExplorer -R files/HVAC/ROOM_3/HVAC_VAV.rddl2 -P rddl.policy.domain.HVAC.HVACPolicy_VAV_det -I inst_hvac_vav_fix -V rddl.viz.ValueVectorDisplay -K 1 -D logs/HVAC_3_Data.txt -L logs/HVAC_3_Label.txt

## Navigation_8x8
./run rddl.sim.DomainExplorer -R files/Navigation/8x8/Navigation_Radius.rddl -P rddl.policy.domain.navigation.FixNavigationPolicy -I is1 -V rddl.viz.ValueVectorDisplay -K 1 -D logs/Navigation_8x8_Data.txt -L logs/Navigation_8x8_Label.txt

## Navigation_10x10
./run rddl.sim.DomainExplorer -R files/Navigation/10x10/Navigation_Radius.rddl -P rddl.policy.domain.navigation.FixNavigationPolicy -I is1 -V rddl.viz.ValueVectorDisplay -K 1 -D logs/Navigation_10x10_Data.txt -L logs/Navigation_10x10_Label.txt

Performance Evaluation
===

## Reservoir_4
./run rddl.sim.DomainExplorer -R files/Reservoir/Reservoir_4/Reservoir.rddl -P rddl.policy.domain.reservoir.FixReservoirPolicy -I is1 -V rddl.viz.ValueVectorDisplay -K 30 >logs/Reservoir_4_log.txt

## Reservoir_3
./run rddl.sim.DomainExplorer -R files/Reservoir/Reservoir_3/Reservoir.rddl -P rddl.policy.domain.reservoir.FixReservoirPolicy -I is1 -V rddl.viz.ValueVectorDisplay -K 30 >logs/Reservoir_3_log.txt

## HVAC_6
./run rddl.sim.DomainExplorer -R files/HVAC/ROOM_6/HVAC_VAV.rddl2 -P rddl.policy.domain.HVAC.HVACPolicy_VAV_det -I inst_hvac_vav_fix -V rddl.viz.ValueVectorDisplay -K 30  >logs/HVAC_6_log.txt

## HVAC_3
./run rddl.sim.DomainExplorer -R files/HVAC/ROOM_3/HVAC_VAV.rddl2 -P rddl.policy.domain.HVAC.HVACPolicy_VAV_det -I inst_hvac_vav_fix -V rddl.viz.ValueVectorDisplay -K 30 >logs/HVAC_3_log.txt

## Navigation_8x8
./run rddl.sim.DomainExplorer -R files/Navigation/8x8/Navigation_Radius.rddl -P rddl.policy.domain.navigation.StochasticNavigationPolicy -I is1 -V rddl.viz.ValueVectorDisplay -K 30 >logs/Navigation_8x8_log.txt

## Navigation_10x10
./run rddl.sim.DomainExplorer -R files/Navigation/10x10/Navigation_Radius.rddl -P rddl.policy.domain.navigation.StochasticNavigationPolicy -I is1 -V rddl.viz.ValueVectorDisplay -K 30 >logs/Navigation_10x10_log.txt

Bayesian Network Display
===

## Reservoir 4
./run rddl.viz.RDDL2Graph -R files/Reservoir/Reservoir_4/Reservoir.rddl -I is1

## Reservoir 3
./run rddl.viz.RDDL2Graph -R files/Reservoir/Reservoir_3/Reservoir.rddl -I is1

## HVAC_6
./run rddl.viz.RDDL2Graph -R files/HVAC/ROOM_6/HVAC_VAV.rddl2 -I inst_hvac_vav_fix

## HVAC_3
./run rddl.viz.RDDL2Graph -R files/HVAC/ROOM_3/HVAC_VAV.rddl2 -I inst_hvac_vav_fix

## Navigation_8x8
./run rddl.viz.RDDL2Graph -R files/Navigation/8x8/Navigation_Radius.rddl -I is1

## Navigation_10x10
./run rddl.viz.RDDL2Graph -R files/Navigation/10x10/Navigation_Radius.rddl -I is1


Parse Log Files to get Mean and std
===
./dofixedpolicies.sh
./run rddl.evaluate.DomainFixPolicyEvaluator -F logs





