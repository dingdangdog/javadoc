# javadoc
Java official document Collection

### Online

Read online at https://javadoc.oldmoon.top

### Statement

This code repository does not provide Java document content. You can visit the website if you want to refer to it: https://javadoc.oldmoon.top. The content of this website is downloaded from the Java official website.

### Compare

- Comparison of Java 11/17/20 version code modules

| Java11-Module         | Java17-Module         | Java20-Module            |
| --------------------- | --------------------- | ------------------------ |
| java.base             | java.base             | java.base                |
| java.compiler         | java.compiler         | java.compiler            |
| java.datatransfer     | java.datatransfer     | java.datatransfer        |
| java.desktop          | java.desktop          | java.desktop             |
| java.instrument       | java.instrument       | java.instrument          |
| java.logging          | java.logging          | java.logging             |
| java.management       | java.management       | java.management          |
| java.management.rmi   | java.management.rmi   | java.management.rmi      |
| java.naming           | java.naming           | java.naming              |
| java.net.http         | java.net.http         | java.net.http            |
| java.prefs            | java.prefs            | java.prefs               |
| java.rmi              | java.rmi              | java.rmi                 |
| java.scripting        | java.scripting        | java.scripting           |
| java.se               | java.se               | java.se                  |
| java.security.jgss    | java.security.jgss    | java.security.jgss       |
| java.security.sasl    | java.security.sasl    | java.security.sasl       |
| java.smartcardio      | java.smartcardio      | java.smartcardio         |
| java.sql              | java.sql              | java.sql                 |
| java.sql.rowset       | java.sql.rowset       | java.sql.rowset          |
| java.transaction.xa   | java.transaction.xa   | java.transaction.xa      |
| java.xml              | java.xml              | java.xml                 |
| java.xml.crypto       | java.xml.crypto       | java.xml.crypto          |
| jdk.accessibility     | jdk.accessibility     | jdk.accessibility        |
| jdk.attach            | jdk.attach            | jdk.attach               |
| jdk.charsets          | jdk.charsets          | jdk.charsets             |
| jdk.compiler          | jdk.compiler          | jdk.compiler             |
| jdk.crypto.cryptoki   | jdk.crypto.cryptoki   | jdk.crypto.cryptoki      |
| jdk.crypto.ec         | jdk.crypto.ec         | jdk.crypto.ec            |
| jdk.dynalink          | jdk.dynalink          | jdk.dynalink             |
| jdk.editpad           | jdk.editpad           | jdk.editpad              |
| jdk.hotspot.agent     | jdk.hotspot.agent     | jdk.hotspot.agent        |
| jdk.httpserver        | jdk.httpserver        | jdk.httpserver           |
| X                     | jdk.incubator.foreign | jdk.incubator.concurrent |
| X                     | jdk.incubator.vector  | jdk.incubator.vector     |
| jdk.jartool           | jdk.jartool           | jdk.jartool              |
| jdk.javadoc           | jdk.javadoc           | jdk.javadoc              |
| jdk.jcmd              | jdk.jcmd              | jdk.jcmd                 |
| jdk.jconsole          | jdk.jconsole          | jdk.jconsole             |
| jdk.jdeps             | jdk.jdeps             | jdk.jdeps                |
| jdk.jdi               | jdk.jdi               | jdk.jdi                  |
| jdk.jdwp.agent        | jdk.jdwp.agent        | jdk.jdwp.agent           |
| jdk.jfr               | jdk.jfr               | jdk.jfr                  |
| jdk.jlink             | jdk.jlink             | jdk.jlink                |
| X                     | jdk.jpackage          | jdk.jpackage             |
| jdk.jshell            | jdk.jshell            | jdk.jshell               |
| jdk.jsobject          | jdk.jsobject          | jdk.jsobject             |
| jdk.jstatd            | jdk.jstatd            | jdk.jstatd               |
| jdk.localedata        | jdk.localedata        | jdk.localedata           |
| jdk.management        | jdk.management        | jdk.management           |
| jdk.management.agent  | jdk.management.agent  | jdk.management.agent     |
| jdk.management.jfr    | jdk.management.jfr    | jdk.management.jfr       |
| jdk.naming.dns        | jdk.naming.dns        | jdk.naming.dns           |
| jdk.naming.rmi        | jdk.naming.rmi        | jdk.naming.rmi           |
| jdk.net               | jdk.net               | jdk.net                  |
| jdk.pack              | X                     | X                        |
| jdk.rmic              | X                     | X                        |
| jdk.scripting.nashorn | X                     | X                        |
| X                     | jdk.nio.mapmode       | jdk.nio.mapmode          |
| jdk.sctp              | jdk.sctp              | jdk.sctp                 |
| jdk.security.auth     | jdk.security.auth     | jdk.security.auth        |
| jdk.security.jgss     | jdk.security.jgss     | jdk.security.jgss        |
| jdk.xml.dom           | jdk.xml.dom           | jdk.xml.dom              |
| jdk.zipfs             | jdk.zipfs             | jdk.zipfs                |

#### JDK11 only

- jdk.pack

> Defines tools for transforming a JAR file into a compressed pack200 file and transforming a packed file into a JAR file, including the *pack200* and *unpack200* tools.

> 定义用于将JAR文件转换为压缩的pack200文件和将打包文件转换为JAR文件的工具，包括pack200和unpack200工具。

- jdk.rmic

> Defines the *rmic* compiler for generating stubs and skeletons using the Java Remote Method Protocol (JRMP) for remote objects.

> 定义 rmic 编译器，用于使用远程对象的 Java 远程方法协议 (JRMP) 生成存根和骨架。

- jdk.scripting.nashorn

> Provides the implementation of Nashorn script engine and the runtime environment for programs written in ECMAScript 5.1.

> 提供Nashorn脚本引擎的实现以及ECMAScript 5.1编写的程序的运行时环境。

#### JDK17 only

- jdk.incubator.foreign

> Defines an API for accessing foreign memory and calling foreign functions, directly from Java.

> 定义了一个 API，用于直接从 Java 访问外部内存和调用外部函数。

- jdk.incubator.vector

> Defines an API for expressing computations that can be reliably compiled at runtime into SIMD instructions, such as AVX instructions on x64, and NEON instructions on AArch64.

> 定义一个用于表达计算的 API，这些计算可以在运行时可靠地编译为 SIMD 指令，例如 x64 上的 AVX 指令和 AArch64 上的 NEON 指令

- jdk.jpackage

> Defines the Java Packaging tool, jpackage.

> 定义 Java 打包工具 jpackage。

-   jdk.nio.mapmode

> Defines JDK-specific file mapping modes.

> 定义 JDK 特定的文件映射模式。

