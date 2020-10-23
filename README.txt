Student: Mike Diep 8334439

Trouble shooting - WINDOWS 10.
Additional steps performed in section "Building and running" in pdf SpringIntro.pdf
Installed Gradle for Windows 10. - Manual Installation.
Performed command - "gradle wrapper" - in the terminal.
Then performed command - "./gradlew bootJar" - from the pdf.

Executing the jar file.
The command "java -jar rabbit-chat-0.0.1-SNAPSHOT.jar --chat.alias=Bob" was insufficient.
The command "java -jar ./build/libs/rabbit-chat-0.0.1-SNAPSHOT.jar --chat.alias=Bob" was used instead.
It needed to path the the .jar file.