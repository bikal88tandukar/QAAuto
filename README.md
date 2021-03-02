# QAAuto
All the Automation Codes
1. Setting Driver                                                                                                                                     //System.setProperty("webdriver.chrome.driver" , "location of file in pc");

2. Creating object driver 
       //ChromeDriver driver = new ChromeDriver();
       
3. Giving driver command to enter any websites 
        //driver.get("www.anywebsites.com");
        
4. Locating webElement by name 
        //driver.findElement(By.name("")).click(); 
        
5. Locating webElement by id 
       //driver.findElement(By.id("").click();
       
7. Locating webElement by xpath 
     //driver.findElement(By.xpath("//input[@id='q']")).submit();
     
9. Typing word in input 
     //driver.findElement(By.id("q")).senkeys("John");
     
11. Navigating 
     //driver.navigate().to("");
     
13. Navigating Back 
     //driver.navigate().back();
     
15. Slow operation 
     //Thread.sleep(2000); and need to add exception
     
17. Handling ALert with accepting 
     //driver.switchTo().alert().accept();
     
19. Handling Alert with not accepting
       //driver.swithTo().alert().dismiss();
       
20. Alert with sending keys 
     //Alert alert = driver.switchTo().alert();               
     //alert.sendkeys(""); //alert.accept();
     
22. Action for RightClick 
     //WebElement rightclickElement = driver.findElement(By.id("q")); 
     //Actions actions = new Actions(driver); 
     //actions.contextClick(rightclickelement).build().perform();
     
24. Action for mouseover
     //action.moveToElement(Element).build().perform();
     
26. Action for Drag and Drop 
     need to swith to frame.  //driver.switchTo.frame(0);  
    find drag element //WebElement dragElementsource = driver.findElement =driver.findElement(By.id("q")); 
    find dropElement // WebElement dropElementTarget = driver.findElement(By.id("i")); 
    //Actions action - new Actions(driver); 
    //action.dragAndDrop(dragElementSource, dropElementTarget.build().perform();
    
28. Leaving frame 
     //driver.switchTo().defaultContent();
     
29. Close driver
     //driver.close(): 
