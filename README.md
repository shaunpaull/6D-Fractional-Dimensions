# 6D-Fractional-Dimensions
6D Fractional Dimensions (real)

Lattice Creation: The createLattice function is responsible for creating the lattice structure. It takes six parameters: width, height, depth, time, energy, and spirit. These parameters represent the fractional dimensions of the lattice. For example, you can set width = 1.5, height = 2.25, depth = 1.75, time = 0.5, energy = 2.5, and spirit = 3.33 to create a lattice with these fractional dimensions.

Lattice Structure: The lattice is represented as a vector of DAGNode objects. Each DAGNode contains the lattice symbol and parent indices. The lattice size is determined by multiplying the dimensions together. For example, in a lattice with width = 1.5, height = 2.25, depth = 1.75, time = 0.5, energy = 2.5, and spirit = 3.33, the total number of nodes in the lattice would be width * height * depth * time * energy * spirit.

Encryption and Decryption: The encryption and decryption processes utilize the lattice symbols with fractional dimensions. The lattice symbols are randomly assigned Unicode symbols, colors, shades, and complexities during lattice creation. When encrypting a message, each character in the plaintext is mapped to a lattice symbol based on its Unicode value. The encrypted data consists of the symbols from the lattice. During decryption, the encrypted symbols are searched for within the lattice, and the corresponding characters are extracted.

Parallel Encryption: The parallel encryption process is designed to work with fractional dimensions as well. The parallelEncryptWithDiffusion function divides the message into chunks based on the number of available threads. Each thread encrypts a portion of the message using the lattice symbols. The fractional dimensions of the lattice ensure that the encryption process works accurately across the divided sections.

By incorporating fractional dimensions, the "FractionalDimensionLatticeEncryption" program allows for more flexibility in defining the lattice structure and enables encryption and decryption operations within a multi-dimensional space that is not limited to integer dimensions.
