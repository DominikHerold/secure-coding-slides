## General

* [.Net Security Cheat Sheet](https://www.owasp.org/index.php/.NET_Security_Cheat_Sheet)

## Design by Contract and Defensive Programming

* [Debug.Assert](https://msdn.microsoft.com/de-de/library/ttcc4x86.aspx)
* [M$ CodeContracts](https://msdn.microsoft.com/de-de/library/dd264808(v=vs.110).aspx)
* [CodeContracts](https://github.com/Microsoft/CodeContracts) - Source code for the CodeContracts tools for .NET
* [New Features in C# 7.0](https://msdn.microsoft.com/de-de/library/dd264808(v=vs.110).aspx) - Missing in C# 7.0?
  * [C# 7.0 Proposal: Method Contracts #119](https://github.com/dotnet/roslyn/issues/119)
  * [C# Champion "Method Contracts" #105](https://github.com/dotnet/csharplang/issues/105)

## Cryptography

* [BouncyCastle](https://bouncycastle.org/) - Together with the .Net System.Security.Cryptography, the reference implementation for cryptographic algorithms on the CLR.
* [libsodium-net](https://github.com/adamcaudill/libsodium-net) - libsodium for .NET - A secure cryptographic library
* [Pkcs11Interop](https://github.com/Pkcs11Interop/Pkcs11Interop) - Managed .NET wrapper for unmanaged PKCS#11 libraries that provide access to the cryptographic hardware
* [SecurityDriven.Inferno](https://github.com/sdrapkin/SecurityDriven.Inferno) - .NET crypto library. Professionally audited.
* [Authenticated Encryption](https://www.codeproject.com/Articles/34380/Authenticated-Encryption)
* [Authenticated Symmetric Encryption in .NET](https://blogs.msdn.microsoft.com/shawnfa/2009/03/17/authenticated-symmetric-encryption-in-net/)
* [Encrypt and decrypt a string](https://stackoverflow.com/questions/202011/encrypt-and-decrypt-a-string)
* [KeePass2.x/KeePassLib/](https://github.com/dlech/KeePass2.x/tree/VS2017/KeePassLib)

### Cryptopals

* Set 1: No. 7 [AES in ECB mode](http://cryptopals.com/sets/1/challenges/7)
* [Cryptopals solutions in C#](https://github.com/defrobo/cryptopals)


### Hashing

* [BLAKE2](https://github.com/BLAKE2/BLAKE2)
* [System.Security.Cryptography where is sha3?](https://social.msdn.microsoft.com/Forums/vstudio/en-US/21005747-2183-4b47-950b-805ae0eccdf6/systemsecuritycryptography-where-is-sha3?forum=vbgeneral)
* [Fork of HashLib project](https://github.com/bonesoul/HashLib)

### Key Derivation Function (KDF)

* [ECDiffieHellmanCng-Klasse](https://msdn.microsoft.com/de-de/library/system.security.cryptography.ecdiffiehellmancng(v=vs.110).aspx)
* [ECDH with Bouncy Castle](https://stackoverflow.com/questions/39648807/ecdh-with-bouncy-castle)
* [Hash It Right: Implementing PBKDF2 in .NET](https://lockmedown.com/hash-right-implementing-pbkdf2-net/)
* [C#/.NET binding for the Argon2 password hash](https://github.com/alipha/csharp-argon2)
* [Fully managed .Net Core implementation of Argon2](https://github.com/mheyman/Isopoh.Cryptography.Argon2)
* [Argon2Kdf-Klasse](https://github.com/dlech/KeePass2.x/blob/VS2017/KeePassLib/Cryptography/KeyDerivation/Argon2Kdf.cs) for KDBX 4 Keepass Database format
* [Fork of http://bcrypt.codeplex.com/](https://github.com/martinsteel/Bcrypt.NET)
* [A .NET implementation of scrypt password hash algorithm.](https://github.com/viniciuschiele/Scrypt)

### Homomorphic Encryption

* [What is Homomorphic Encryption, and Why Should I Care?](https://community.embarcadero.com/blogs/entry/what-is-homomorphic-encryption-and-why-should-i-care-38566)
* [A Math Primer for Gentry's Fully Homomorphic Encryption](https://community.embarcadero.com/blogs/entry/a-math-primer-for-gentrys-fully-homomorphic-encryption-38577)
* [Fully homomorphic encryption schemes](http://cryptowiki.net/index.php?title=Fully_homomorphic_encryption_schemes)
* [Homomorphic Encryption is Cool, and You Should NOT Use It](https://info.townsendsecurity.com/bid/72771/Homomorphic-Encryption-is-Cool-and-You-Should-NOT-Use-It)

## Transport Security 

* [SslStream-Klasse](https://msdn.microsoft.com/de-de/library/system.net.security.sslstream(v=vs.110).aspx)
* [SslProtocols-Enumeration](https://msdn.microsoft.com/de-de/library/system.security.authentication.sslprotocols(v=vs.110).aspx)
* [C# SSL Socket Server and Client - multiple clients](https://www.youtube.com/watch?v=DPO3yohpElk)
* [TLS 1.2 and .NET Support: How to Avoid Connection Errors](http://blogs.perficient.com/microsoft/2016/04/tsl-1-2-and-net-support/)
* [How to: Use Transport Security and Message Credentials](https://docs.microsoft.com/en-us/dotnet/framework/wcf/feature-details/how-to-use-transport-security-and-message-credentials)
* [C# wrapper for the popular OpenSSL libraries](https://github.com/openssl-net/openssl-net)
* [SSH.NET is a Secure Shell (SSH) library for .NET, optimized for parallelism.](https://github.com/sshnet/SSH.NET)
* [Fork of SharpSSH](https://github.com/jbogard/SharpSSH)
* [How to enable server side SSL for gRPC?](https://stackoverflow.com/questions/37714558/how-to-enable-server-side-ssl-for-grpc)-> [grcp in C#](https://grpc.io/docs/quickstart/csharp.html)
* [http://noiseprotocol.org/](http://noiseprotocol.org/)
* [Let's Encrypt](https://letsencrypt.org/ "Let’s Encrypt is a free, automated, and open Certificate Authority.") - Let’s Encrypt is a free, automated, and open Certificate Authority.

## Frameworks and Libraries

* [zxcvbn-cs](https://github.com/mickford/zxcvbn-cs "C#/.NET port of Dan Wheeler/DropBox's Zxcvbn JS password strength estimation library") - C#/.NET port of Dan Wheeler/DropBox's Zxcvbn JS password strength estimation library

## Robustness

* [Polly](https://github.com/App-vNext/Polly) - Express transient-exception-handling and resilience policies such as Retry, Wait-and-Retry, Circuit Breaker, and Bulkhead Isolation in a fluent manner. Fully thread-safe and full async support.  (4.0 / 4.5 / .Net Core / .Net Standard / Xamarin).
* [ReactiveUI](https://github.com/reactiveui/reactiveui/) - An MVVM framework for .NET that integrates the Reactive Extensions (Rx) framework, enabling developers to build elegant, testable applications using WPF, Windows Store Apps, WP8 or Xamarin.
* [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET) - The Reactive Extensions (Rx) is a library for composing asynchronous and event-based programs using observable sequences and LINQ-style query operators


## Secure Coding

* [Secure Coding Guidelines](https://msdn.microsoft.com/en-us/library/d55zzx87(v=vs.90).aspx)
* [Secure coding in C#](https://de.slideshare.net/SiddharthBezalwar/secure-coding-in-c)
* [.NET Secure Memory Structures](https://stackoverflow.com/questions/1166952/net-secure-memory-structures)