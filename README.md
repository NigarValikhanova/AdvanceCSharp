# AdvanceCSharp

<h2>Lesson 1 <br> 05.05.2024 </h1>

✅ .NET ecosystem nədir?
<br>
✅ .NET vs C#. C# və .NET develop kimlərdir?
<br>
✅ C# kompilyasiya prosesi necə baş verir?
<br>
✅ .NET-də dillərarası inteqrasiya
<br>
✅ Process loader və önəmi
<br>
✅ Common Language Runtime (CLR)
<br>
✅ Common Type System (CTS)
<br>
✅ Common Language Specification (CLS)
<br>
✅ Just-İn-Time (JİT) Compiler
<br>
✅ Assemble və Disassamble prosesləri
<br>
✅ İL dili və önəmi
<br>
✅ İL dili ilə reverse engineering
<br>
✅ Manifest və Metadata
<br>
✅ Praktiki nümunələrdə dillərarası integrasiya (VB və C#)
<br>
✅ İL dili vasitəsilə Stack-lə iş
<br>
✅ İL dilində Obyektyönümlü Proqramlaşdırma
<br>

<h4> Manifest </h4>

In the context of C# and the .NET framework, a **manifest** refers to an integral part of an assembly, which is a collection of files that are compiled from C# or other .NET languages. The manifest contains important metadata about the contents and behavior of the assembly.

Here are the key components and functions of a manifest in a .NET assembly:

1. **Assembly Metadata**: This includes the assembly's name, version, culture, and strong name information (if the assembly is signed). This metadata helps ensure that the correct version of an assembly is loaded at runtime.

2. **Type Information**: The manifest records the types and their members that are exported from the assembly, allowing other assemblies to understand what is available for use without needing to reference the entire assembly content.

3. **File List**: It lists all the other files that make up the assembly, such as other assemblies or resources that it depends on. This ensures that all necessary components are available for the application to function.

4. **Reference Information**: The manifest details information about other assemblies that this assembly depends on, including their names and versions. This is crucial for assembly resolution at runtime to maintain compatibility and functionality.

5. **Security Permissions**: If applicable, the manifest can also include security information that specifies the permissions required by the assembly, helping to enforce security constraints.

Overall, the manifest acts like a "table of contents" for the assembly, providing all necessary information about its composition and dependencies. This makes the manifest critical for assembly deployment, versioning, and security in the .NET framework environment.
