# inifinispan-svc-posmgr
Infinispan Position Management Experiment 

posmgr-cli/PositionMonitorApp - watch changing positions
posmgr-testdata/PositionLoaderApp - load 50k events
posmgr-testdata/ServerSidePositionMgmtApp - load 50k event with svc position management
posmgr-webclient/PositionHttpHandler - /positionID query
posmgr-webclient/PositionListHttpHandler - /clientID query for all positions of a client
posmgr-webclient/PositionQueryWebCQHandler - CQ for position monitoring
