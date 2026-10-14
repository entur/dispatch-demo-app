# dispatch-demo-app

Public source repo for the dispatch relay demo. A push to `main` runs the tests, then the `entur/dispatch-relay`
action asks the relay to dispatch `deploy.yml` in the private `henrik242/dispatch-demo-app-deployment-config`. No secrets; the
relay URL is the repo variable `DISPATCH_RELAY_URL`, so the demo stays on the dev relay. `probe.yml` calls the relay
inline to show rejections.

See `entur/dispatch-relay` for setup.

