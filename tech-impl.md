## Technical support for implementation

### RUST Libraries
* [rmcp](https://docs.rs/rmcp/latest/rmcp/) for RUST MCP SDK
* [serde](https://serde.rs/) for serialization and deserialization, JSON formats
* [tonic](https://docs.rs/tonic/latest/tonic/) for RUST implementation of gRPC
* [tokio](https://tokio.rs/) for asynchronous programming
* [SocketCAN](https://docs.rs/socketcan/latest/socketcan/) for CANBus interfacing
* [rumqttc](https://docs.rs/rumqttc/latest/rumqttc/) for MQTT
* Custom SOME/IP libraries (still exploring as not yet found official/popular one)
* [D-Bus Bindings](https://docs.rs/dbus/latest/dbus/) for RUST
  
### C++ Libraries
* [vsomeip](https://covesa.global/project/vsomeip/)
* [gRPC](https://grpc.io/docs/languages/cpp/quickstart/) C++ APIs
* SocketCAN APIs (BSD Socket API) supported by Linux Kernel
* [Paho](https://github.com/eclipse-paho/paho.mqtt.cpp) library for MQTT

### Host side tools - for testing/quick prototyping/inspection
* [MCP Inspector](https://modelcontextprotocol.io/docs/tools/inspector)
* [FastMCP](https://pypi.org/project/fastmcp/) , python package for initial prototyping (not for end deployment into Vehicle ECUs)
* [MCP CLI](https://pypi.org/project/mcp-cli/)
