# On-Off-Attack

Here, we present Rebeca code that is based on actor model. The model is a Blockchain architecture and shows the spot where the fake transaction is jnjected. It consists of miner actors. The dishonest miner stores the fake transactions in a pending pool and ready to append transactions while building a new block. The distributed ledger (Blockchain) is defined by a n * 8 list. The valiable n is current number of built blocks and eight specifies [minerID, BlockID, utx1, tx1, utx2, tx2, utx3, tx3] which are miner, block and transactions identity numbers. Therefore, we easily can find out which transactions are stored in the distributed ledger and show the infected spot.
