# Curated list of TPM (Trusted Platform Module) projects

- [Keylime](https://keylime.dev) _[active]_ <br>
Open source TPM remote attestation softare.

- [TPM2 TSS](https://github.com/tpm2-software/tpm2-tss) _[active]_ <br>
Open source implementation of TCG TPM2 Software Stack (TSS2).

- [TPM2 PKCS#11](https://github.com/tpm2-software/tpm2-pkcs11) _[active]_ <br>
A PKCS#11 interface for TPM2 hardware.

- [TPM2 tools](https://github.com/tpm2-software/tpm2-tools) _[active]_ <br>
TPM 2.0 tools based on tpm2-tss.

- [TPM2 ABRMD](https://github.com/tpm2-software/tpm2-abrmd) _[active]_ <br>
System daemon implementing TPM2 access broker (TAB) and resource manager (RM) spec from the TCG.o

- [TPM2 TSS engine](https://github.com/tpm2-software/tpm2-tss-engine) _[active]_ <br>
Cryptographic engine for OpenSSL for TPM 2.0, using the tpm2-tss. Supports RSA decryption/signatures and ECDSA signatures.

- [TPM JavaScript emulator + demo](https://google.github.io/tpm-js/) _[active]_ <br>
TPM-JS lets you experiment with a software Trusted Platform Module (TPM) in your browser.

- [Cryptsetup](https://gitlab.com/cryptsetup/cryptsetup/) _[active]_ <br>
Cryptsetup and LUKS - open-source disk encryption

- [TSS.MSR](https://github.com/Microsoft/TSS.MSR) _[active]_ <br>
TPM Software Stack implementation from Microsoft Research.

- [libtpms](https://github.com/stefanberger/libtpms) _[active]_ <br>
Library providing software emulation of TPM 1.2 and TPM 2.0. Targets the integration of TPM functionality into hypervisors (Qemu).

- [wolfTPM](https://github.com/wolfSSL/wolfTPM) _[active]_ <br>
Portable TPM 2.0 library designed for embedded use.

- [Microsoft TPM 2.0 ref](https://github.com/Microsoft/ms-tpm-20-ref) _[active]_ <br>
Reference implementation of the TPM 2.0 specification by Microsoft.

- [IBM TPM2 TSS](https://sourceforge.net/projects/ibmtpm20tss/) _[active]_ <br>
IBM's implementation of TPM Software Stack. Functionality equivalent to TCG TSS, but different interface.

- [IBM Software TPM2](https://sourceforge.net/projects/ibmswtpm2/) _[active]_ <br>
IBM's software TPM 2.0 simulator.

- [SWTPM](https://github.com/stefanberger/swtpm) _[active]_ <br>
Libtpms-based TPM emulator with socket, character device, and Linux CUSE interface.

- [IBM TPM Attestation Client Server](https://sourceforge.net/projects/ibmtpm20acs/) _[active]_ <br>
Code for TCG attestation application.

- [Simple TPM PK11](https://github.com/ThomasHabets/simple-tpm-pk11)  _[last commit: 2020]_ <br>
Simple PKCS11 provider for TPM chips. Supports OpenSSH.

- [TPM emulator](https://github.com/PeterHuewe/tpm-emulator) _[last commit 2018]_ <br>
A Software-based TPM and MTM Emulator. TPM 1.2 only.

- [tpmtopt](https://github.com/mjg59/tpmtotp) _[last commit 2016]_ <br>
Remote attestation of boot state using a TOTP token in another device. Can be used with e.g. Google Authenticator. Before requesting the disk decryption passphrase, a TOTP token is displayed on the screen that can be checked using another device (phone).

- [Python TSS](https://github.com/mjg59/python-tss) _[last commit: 2016]_ <br>
Python library for interfacing with TPMs.

- [TrustedGRUB2](https://github.com/Rohde-Schwarz-Cybersecurity/TrustedGRUB2) _[deprecated]_ <br>
Extension to standard GRUB2 bootloader to offer TPM support for granting integrity of the boot process (trusted boot).

- [TPM2 PK11](https://github.com/irtimmer/tpm2-pk11)  _[deprecated]_ <br>
PKCS#11 module for TPM 2.0. Supports OpenSSH, Firefox and GnuPG.

### Shell scripts / guides
- [Linux LUKS TPM boot](https://github.com/fox-it/linux-luks-tpm-boot) _[last commit: 2018]_ <br>
Uses LUKS and TrustedGRUB2 to emulate the behaviour of Microsoft's Bitlocker (seamless disk encryption/decryption).

- [TPM2-LUKS](https://github.com/rqou/tpm2-luks) _[last commit: 2017]_ <br>
Setup of Bitlocker-like encryption using TPM 2.0 and LUKS.
