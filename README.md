# rlpae - RLP as used in aeternity
Fork of RLP from go-ethereum, except that:

go-ethereum rlp
`0x80` -> [] or int(0)

rlpae
`0x80` -> []
`bytearray(0)` -> int(0)
