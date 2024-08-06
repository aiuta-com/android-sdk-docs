# Using the Bill of Materials

In addition to the usual dependency plug-in, you can use [Bill of Materials](https://developer.android.com/jetpack/compose/bom) for better
versioning of all Aiuta SDK dependencies

<tabs>
    <tab title="Gradle (Kotlin)">
    <code-block lang="kotlin">
        dependencies {
            val fashionVersion: String = "%latest_fashion_version%"
            implementation(platform("com.aiuta:fashionsdk-bom:$fashionVersion"))
            implementation("com.aiuta:fashionsdk")
            // ...
        }
    </code-block>
    </tab>
</tabs>

<note>
    <p>
        You also can check last version of BOM on <a href="https://central.sonatype.com/artifact/com.aiuta/fashionsdk-bom">Central Sonatype</a>
    </p>
</note>