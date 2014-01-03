# Channel Design

Each channel needs to be completely isolated. This rules out all 4 channel
ADCs, because they would break isolation.

This is a practical restriction; because the end user doesn't necessarily know
the internal structure of the ChaosMeter, and the user might wish to measure
completely different potentials for all channels.

This means that we need to have separate isolation, resistor dividor networks,
relais and ADCs for each channel, driving up costs.

