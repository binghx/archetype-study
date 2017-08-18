### 生成项目目录架构:
src--

     |

      main

        |

	 --java

	     |

	      --自己定义的包名

	      		|

			 architecture(架构)

			 base(jdk基础)

			 designpattern(设计模式)

			 effective(最佳实践)

			 main(核心demo)

     |

      test

      	|

	 --java

	     |

	      --自己定义的包名

	      		|

			 architecture(架构)

			 base(jdk基础)

			 designpattern(设计模式)

			 effective(最佳实践)

			 main(核心demo)


### 本项目编译安装

```Java

mvn clean install

```

### 使用本项目generate maven 项目

```Java
mvn archetype:generate \ 
-DarchetypeGroupId=me.zixing.archetype \
-DarchetypeArtifactId=archetype-study \
-DarchetypeVersion=1.0

```

### 项目交互创建过程中，需要输入的参数

groupId

artifactId

version(默认1.0-SNAPSHOT)

java_source_version(jdk版本)

java_target_version(编译目标jdk版本)
