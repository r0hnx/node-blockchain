# BlockChain in Node.js

A simple implementation of blockchain and cryptocurrency wallet in Node.js and TypeScript (**for learning purposes**)

# Usage

```bash
git clone <repo>
cd repo
npm install
npm start
```

# Expected Output

```bash
**** 🔨 MINING 🔨 ****
Solved: 98249
**** 🔨 MINING 🔨 ****
Solved: 68529
**** 🔨 MINING 🔨 ****
Solved: 236136
Chain {
  chain: [
    Block {
      prevHash: '',
      transaction: [Transaction],
      ts: 1614626620292,
      nonce: 717070358
    },
    Block {
      prevHash: 'cdb968414152632d69c4a3d6bfea3ae03f842c933f1e58a4125baf1fa445f9c4',
      transaction: [Transaction],
      ts: 1614626620625,
      nonce: 786148775
    },
    Block {
      prevHash: 'ba571352eda3946284070addf5e6591057877b428343af8d8caa0e6b3c52baca',
      transaction: [Transaction],
      ts: 1614626622158,
      nonce: 736597509
    },
    Block {
      prevHash: '71586cf146b49bdac0d1292e7751c02ee8f3971be1236a36f34a60d4dc0271ac',
      transaction: [Transaction],
      ts: 1614626622883,
      nonce: 178221624
    }
  ]
}
```