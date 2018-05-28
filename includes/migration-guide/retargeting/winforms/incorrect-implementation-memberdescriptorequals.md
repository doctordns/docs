### Incorrect implementation of MemberDescriptor.Equals

|   |   |
|---|---|
<<<<<<< HEAD
|Details|Original implementation of &quot;Equals&quot; method was comparing two different string properties from the objects under comparison: category name to description string. The fix is to compare &quot;category&quot; of first object to &quot;category&quot; of the second one and &quot;description&quot; to &quot;description&quot;. MemberDescriptorEqualsReturnsFalseIfEquivalent configuration value can be set to true to opt out of the new behavior if targeting 4.6.2 or to false to enable this fix when targeting framework version is below 4.6.2.|
|Suggestion|If your application depends on MemberDescriptor.Equals sometimes returning false when descriptors are equivalent, and you are targeting 4.6.2 version of the .NET Framework, you have several options:<ul><li>Make code changes to compare &quot;category&quot; and &quot;description&quot; fields manually in addition to running Equals method.</li><li>Opt out from this change by adding the following value to the app.config file:</li></ul><pre><code>&lt;runtime&gt;&#13;&#10;&lt;AppContextSwitchOverrides value=&quot;Switch.System.MemberDescriptorEqualsReturnsFalseIfEquivalent=true&quot; /&gt;&#13;&#10;&lt;/runtime&gt;&#13;&#10;</code></pre>If your application targets 4.6.1 or lower version of the .NET Framework, and you want this change enabled, you can set the compatibility switch to false by adding the following value to the app.config file:<pre><code>&lt;runtime&gt;&#13;&#10;&lt;AppContextSwitchOverrides value=&quot;Switch.System.MemberDescriptorEqualsReturnsFalseIfEquivalent=false&quot; /&gt;&#13;&#10;&lt;/runtime&gt;&#13;&#10;</code></pre>|
=======
|Details|The original implementation of the <xref:System.ComponentModel.MemberDescriptor.Equals%2A?displayProperty=nameWithType> method compares two different string properties from the objects being compared: the category name and the description string. The fix is to compare the <xref:System.ComponentModel.MemberDescriptor.Category> of the first object to the <xref:System.ComponentModel.MemberDescriptor.Category> of the second one, and the <xref:System.ComponentModel.MemberDescriptor.Description> of the first to the <xref:System.ComponentModel.MemberDescriptor.Description> of the second.|
|Suggestion|If your application depends on <xref:System.ComponentModel.MemberDescriptor.Equals%2A?displayProperty=nameWithType> sometimes returning <code>false</code> when descriptors are equivalent, and you are targeting the .NET Framework 4.6.2 or later, you have several options:<ol><li>Make code changes to compare the <xref:System.ComponentModel.MemberDescriptor.Category> and <xref:System.ComponentModel.MemberDescriptor.Description> fields manually in addition to calling the <xref:System.ComponentModel.MemberDescriptor.Equals%2A?displayProperty=nameWithType> method.</li><li>Opt out of this change by adding the following value to the app.config file:</li></ol><pre><code class="lang-xml">&lt;runtime&gt;&#13;&#10;&lt;AppContextSwitchOverrides value=&quot;Switch.System.MemberDescriptorEqualsReturnsFalseIfEquivalent=true&quot; /&gt;&#13;&#10;&lt;/runtime&gt;&#13;&#10;</code></pre>If your application targets .NET Framework 4.6.1 or earlier and is running on the .NET Framework 4.6.2 or later and you want this change enabled, you can set the compatibility switch to <code>false</code> by adding the following value to the app.config file:<pre><code class="lang-xml">&lt;runtime&gt;&#13;&#10;&lt;AppContextSwitchOverrides value=&quot;Switch.System.MemberDescriptorEqualsReturnsFalseIfEquivalent=false&quot; /&gt;&#13;&#10;&lt;/runtime&gt;&#13;&#10;</code></pre>|
>>>>>>> upstream/master
|Scope|Edge|
|Version|4.6.2|
|Type|Retargeting|
|Affected APIs|<ul><li><xref:System.ComponentModel.MemberDescriptor.Equals(System.Object)?displayProperty=nameWithType></li></ul>|
<<<<<<< HEAD
|Analyzers|<ul><li>CD0150</li></ul>|
=======
>>>>>>> upstream/master

