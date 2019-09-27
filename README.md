
# Basic SNMP DSLink

A Basic DSLink for Simple Network Management Protocol.

## License

Apache 2.0

## Usage

After adding an Agent, you can create folders within its node, and add OIDs anywhere within its folder structure.
Adding an OID sends a GET request to the agent to get that OID's value. The dslink will continue to send GET requests
and update the OID's value regularly, every refreshInterval seconds, as specified when adding an agent. After adding
an OID, you can call its set action to send a SET request.

## Internals

Uses the SNMP4J Java Library.






