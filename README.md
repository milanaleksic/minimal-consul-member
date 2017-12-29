# minimal_consul_member

This is a tiny library meant to be used by Go applications that want to:
 
 1. expose a server on an internal port (only locally available) where `/healthz`
   endpoint will be exposed with simple (non-configurable at this point) health check 
 1. register a service in Consul with a check using the one mentioned in 1)
