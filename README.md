# Hellolibrary:成为开源贡献者的第一步



    allprojects {

        repositories   
        {      
            jcenter()
            ...
            maven {url "https://jitpack.io" }
        }
    }


    dependencies {

     compile 'com.github.wangchunfei:Hellolibrary:v1.1'
    
    }


    CustomUtil.getMyHero() 
