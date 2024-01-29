An example of a [React-leaflet](https://react-leaflet.js.org) implementation including [leaflet-extra-markers](https://www.npmjs.com/package/leaflet-extra-markers) and [react-leaflet-cluster](https://www.npmjs.com/package/react-leaflet-cluster).

[Demo](https://codesandbox.io/p/github/Thomas-Martin-1998/React-Leaflet-ExtraMarker-Clusters/master?layout=%257B%2522sidebarPanel%2522%253A%2522GIT%2522%252C%2522rootPanelGroup%2522%253A%257B%2522direction%2522%253A%2522horizontal%2522%252C%2522contentType%2522%253A%2522UNKNOWN%2522%252C%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522id%2522%253A%2522ROOT_LAYOUT%2522%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522contentType%2522%253A%2522UNKNOWN%2522%252C%2522direction%2522%253A%2522vertical%2522%252C%2522id%2522%253A%2522clrv82iej00063b5vufif3qd5%2522%252C%2522sizes%2522%253A%255B70%252C30%255D%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522contentType%2522%253A%2522EDITOR%2522%252C%2522direction%2522%253A%2522horizontal%2522%252C%2522id%2522%253A%2522EDITOR%2522%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL%2522%252C%2522contentType%2522%253A%2522EDITOR%2522%252C%2522id%2522%253A%2522clrv82iei00023b5vhmzaucvb%2522%257D%255D%257D%252C%257B%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522contentType%2522%253A%2522SHELLS%2522%252C%2522direction%2522%253A%2522horizontal%2522%252C%2522id%2522%253A%2522SHELLS%2522%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL%2522%252C%2522contentType%2522%253A%2522SHELLS%2522%252C%2522id%2522%253A%2522clrv82iej00043b5vhcf0885d%2522%257D%255D%252C%2522sizes%2522%253A%255B100%255D%257D%255D%257D%252C%257B%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522contentType%2522%253A%2522DEVTOOLS%2522%252C%2522direction%2522%253A%2522vertical%2522%252C%2522id%2522%253A%2522DEVTOOLS%2522%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL%2522%252C%2522contentType%2522%253A%2522DEVTOOLS%2522%252C%2522id%2522%253A%2522clrv82iej00053b5vx51wi8vc%2522%257D%255D%252C%2522sizes%2522%253A%255B100%255D%257D%255D%252C%2522sizes%2522%253A%255B50%252C50%255D%257D%252C%2522tabbedPanels%2522%253A%257B%2522clrv82iei00023b5vhmzaucvb%2522%253A%257B%2522id%2522%253A%2522clrv82iei00023b5vhmzaucvb%2522%252C%2522tabs%2522%253A%255B%257B%2522id%2522%253A%2522clryz3kmq003m3b5uv5cstgkc%2522%252C%2522mode%2522%253A%2522permanent%2522%252C%2522type%2522%253A%2522FILE%2522%252C%2522filepath%2522%253A%2522%252Fsrc%252Fconstants%252FColors.ts%2522%252C%2522state%2522%253A%2522IDLE%2522%257D%255D%252C%2522activeTabId%2522%253A%2522clryz3kmq003m3b5uv5cstgkc%2522%257D%252C%2522clrv82iej00053b5vx51wi8vc%2522%253A%257B%2522id%2522%253A%2522clrv82iej00053b5vx51wi8vc%2522%252C%2522activeTabId%2522%253A%2522clryz58ur005p3b5urzxp0ugr%2522%252C%2522tabs%2522%253A%255B%257B%2522type%2522%253A%2522TASK_PORT%2522%252C%2522taskId%2522%253A%2522start%2522%252C%2522port%2522%253A3000%252C%2522id%2522%253A%2522clrv8g24c002z3b5tv6einj2z%2522%252C%2522mode%2522%253A%2522permanent%2522%252C%2522path%2522%253A%2522%2522%257D%252C%257B%2522type%2522%253A%2522SETUP_TASKS%2522%252C%2522id%2522%253A%2522clryz58ur005p3b5urzxp0ugr%2522%252C%2522mode%2522%253A%2522permanent%2522%257D%255D%257D%252C%2522clrv82iej00043b5vhcf0885d%2522%253A%257B%2522id%2522%253A%2522clrv82iej00043b5vhcf0885d%2522%252C%2522activeTabId%2522%253A%2522clrv84j3a006r3b5vrpl7r4s2%2522%252C%2522tabs%2522%253A%255B%257B%2522id%2522%253A%2522clrv82iej00033b5vush26sxb%2522%252C%2522mode%2522%253A%2522permanent%2522%252C%2522type%2522%253A%2522TERMINAL%2522%252C%2522shellId%2522%253A%2522clrv82jbx0015ecjpcr1oeir4%2522%257D%252C%257B%2522type%2522%253A%2522TASK_LOG%2522%252C%2522taskId%2522%253A%2522CSB_RUN_OUTSIDE_CONTAINER%253D1%2520devcontainer%2520templates%2520apply%2520--template-id%2520%255C%2522ghcr.io%252Fdevcontainers%252Ftemplates%252Ftypescript-node%255C%2522%2520--template-args%2520%27%257B%257D%27%2520--features%2520%27%255B%255D%27%2522%252C%2522id%2522%253A%2522clrv84i70004p3b5veya2apj6%2522%252C%2522mode%2522%253A%2522permanent%2522%257D%252C%257B%2522type%2522%253A%2522TASK_LOG%2522%252C%2522taskId%2522%253A%2522start%2522%252C%2522id%2522%253A%2522clrv84j3a006r3b5vrpl7r4s2%2522%252C%2522mode%2522%253A%2522permanent%2522%257D%255D%257D%257D%252C%2522showDevtools%2522%253Atrue%252C%2522showShells%2522%253Atrue%252C%2522showSidebar%2522%253Atrue%252C%2522sidebarPanelSize%2522%253A15%257D)

