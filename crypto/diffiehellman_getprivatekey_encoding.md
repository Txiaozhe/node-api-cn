<!-- YAML
added: v0.5.0
-->
* `encoding` {string}
* Returns: {Buffer | string}

Returns the Diffie-Hellman private key in the specified `encoding`,
which can be `'latin1'`, `'hex'`, or `'base64'`. If `encoding` is provided a
string is returned; otherwise a [`Buffer`][] is returned.

