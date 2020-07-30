# NICS Crypto

NICS Crypto is a cryptography library written in Java, which extends Java Cryptography Architecture (JCA) to support non-traditional cryptographic primitives, such as Proxy Re-Encryption. Currently, it is at a very first stage and under heavy development.

Current implemented schemes:

    Proxy Re-Encryption:

        AFGH scheme: Ateniese, G., Fu, K., Green, M., & Hohenberger, S. (2006). Improved proxy re-encryption schemes with applications to secure distributed storage. ACM Transactions on Information and System Security (TISSEC), 9(1), 1-30.
        LV11 scheme: Libert, B., & Vergnaud, D. (2011). Unidirectional chosen-ciphertext secure proxy re-encryption. Information Theory, IEEE Transactions on, 57(3), 1786-1802.

NICS Crypto uses the jPBC library for pairing-based cryptography.

NICS Crypto is free and released under the GNU Lesser General Public License.
