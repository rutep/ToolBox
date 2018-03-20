hello: hello.java helloSecond.java
	javac hello.java helloSecond.java && java hello helloSecond

helloFirst: hello.class
	java hello

helloSecond: helloSecond.class
	java helloSecond

clean: 
	rm *.class
