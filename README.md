<div align="center">
  <a href="https://github.com/colyseus/colyseus">
    <img src="https://github.com/colyseus/colyseus/blob/master/media/header.png?raw=true" />
  </a>
  <br>
  <br>
  <a href="https://npmjs.com/package/colyseus">
    <img src="https://img.shields.io/npm/dm/colyseus.svg?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAQAAAC1+jfqAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAAAmJLR0QAAKqNIzIAAAAJcEhZcwAADsQAAA7EAZUrDhsAAAAHdElNRQfjAgETESWYxR33AAAAtElEQVQoz4WQMQrCQBRE38Z0QoTcwF4Qg1h4BO0sxGOk80iCtViksrIQRRBTewWxMI1mbELYjYu+4rPMDPtn12ChMT3gavb4US5Jym0tcBIta3oDHv4Gwmr7nC4QAxBrCdzM2q6XqUnm9m9r59h7Rc0n2pFv24k4ttGMUXW+sGELTJjSr7QDKuqLS6UKFChVWWuFkZw9Z2AAvAirKT+JTlppIRnd6XgaP4goefI2Shj++OnjB3tBmHYK8z9zAAAAJXRFWHRkYXRlOmNyZWF0ZQAyMDE5LTAyLTAxVDE4OjE3OjM3KzAxOjAwGQQixQAAACV0RVh0ZGF0ZTptb2RpZnkAMjAxOS0wMi0wMVQxODoxNzozNyswMTowMGhZmnkAAAAZdEVYdFNvZnR3YXJlAHd3dy5pbmtzY2FwZS5vcmeb7jwaAAAAAElFTkSuQmCC">
  </a>
  <a href="https://patreon.com/endel" title="Donate to this project using Patreon">
    <img src="https://img.shields.io/badge/dynamic/json?logo=patreon&style=for-the-badge&color=%23e85b46&label=Patreon&query=data.attributes.patron_count&suffix=%20backers&url=https%3A%2F%2Fwww.patreon.com%2Fapi%2Fcampaigns%2F365642" alt="Patreon donate button"/>
  </a>
  <a href="https://discuss.colyseus.io" title="Discuss on Forum">
    <img src="https://img.shields.io/badge/discuss-on%20forum-brightgreen.svg?style=for-the-badge&colorB=0069b8&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAQAAAC1+jfqAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAAAmJLR0QAAKqNIzIAAAAJcEhZcwAADsQAAA7EAZUrDhsAAAAHdElNRQfjAgETDROxCNUzAAABB0lEQVQoz4WRvyvEARjGP193CnWRH+dHQmGwKZtFGcSmxHAL400GN95ktIpV2dzlLzDJgsGgGNRdDAzoQueS/PgY3HXHyT3T+/Y87/s89UANBKXBdoZo5J6L4K1K5ZxHfnjnlQUf3bKvkgy57a0r9hS3cXfMO1kWJMza++tj3Ac7/LY343x1NA9cNmYMwnSS/SP8JVFuSJmr44iFqvtmpjhmhBCrOOazCesq6H4P3bPBjFoIBydOk2bUA17I080Es+wSZ51B4DIA2zgjSpYcEe44Js01G0XjRcCU+y4ZMrDeLmfc9EnVd5M/o0VMeu6nJZxWJivLmhyw1WHTvrr2b4+2OFqra+ALwouTMDcqmjMAAAAldEVYdGRhdGU6Y3JlYXRlADIwMTktMDItMDFUMTg6MTM6MTkrMDE6MDAC9f6fAAAAJXRFWHRkYXRlOm1vZGlmeQAyMDE5LTAyLTAxVDE4OjEzOjE5KzAxOjAwc6hGIwAAABl0RVh0U29mdHdhcmUAd3d3Lmlua3NjYXBlLm9yZ5vuPBoAAAAASUVORK5CYII=" alt="Discussion forum" />
  </a>
  <a href="https://discord.gg/RY8rRS7">
    <img src="https://img.shields.io/discord/525739117951320081.svg?style=for-the-badge&colorB=7581dc&logo=discord&logoColor=white">
  </a>
  <h3>
     Multiplayer Game Client for <a href="https://haxe.org/">Haxe</a> <br /><a href="https://docs.colyseus.io/getting-started/haxe-client/">View documentation</a>
  </h3>
</div>

| Description | Status |
| ------| -------|
| Master Branch Build Status | [![Build Status](https://travis-ci.org/colyseus/colyseus-hx.svg?branch=master)](https://travis-ci.org/colyseus/colyseus-hx) |

## Running the demo project

First, download and install [Haxe](https://haxe.org/download/).

The [`example`](https://github.com/colyseus/colyseus-hx/blob/master/example/openfl) project can be compiled to `html5`, `neko`, `cpp`, `ios`, etc.

It uses the `state_handler` room from the [colyseus-examples](https://github.com/colyseus/colyseus-examples) project, which you can find [here](https://github.com/colyseus/colyseus-examples/blob/master/rooms/02-state-handler.ts).

### Compiling the demo project to `html5`

```
git clone https://github.com/colyseus/colyseus-hx.git
cd colyseus-hx/example/openfl
haxelib install openfl
haxelib install lime
haxelib install colyseus-websocket
haxelib run lime test project.xml html5
```

## Dependencies

[colyseus-hx](https://github.com/colyseus/colyseus-hx) depends on [`colyseus-websocket`](https://github.com/colyseus/colyseus-websocket-hx)

## License

MIT
