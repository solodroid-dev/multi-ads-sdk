# ads-network-sdk
A library for displaying ads from multiple ad networks

Implementation build.gradle (Module: app)
<pre>
implementation 'com.github.solodroid-dev:multi-ads-sdk:2.+'
</pre>

Open settings.gradle (Project Settings) and update the dependencyResolutionManagement
<pre>
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        mavenCentral()
        maven { url 'https://jitpack.io' }
        maven { url 'https://android-sdk.is.com/' }
        maven { url 'https://unity3ddist.jfrog.io/artifactory/unity-mediation-mvn-prod-local/' }
    }
}
</pre>
