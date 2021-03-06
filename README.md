# SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog
<b> How to use AWS Systems Manager Automation to Install a LAMP Web Server &amp; Hosting a WordPress Blog on Amazon Linux or Amazon Linux 2 </b>

<p><span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;"><b>Background:</b></span></p>
<p>
    <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><I>In general we follow the <b><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-tutorials.html" target="_blank">documentation</a></b>&nbsp;to get started. Now, we have SSM Service which can do this in an automated fashion which is quicker and does all your job without any direct user interaction on OS level. </I> </span></font>
</p>
<p>
    <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><br></span></font>
</p>
<p><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px; font-weight: 700;"> <b> Which SSM Automation Documents you can use ? </b> </span><br></p>
<p><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;">You can use below Automated Documents to achieve this task :</span></p>
<p><b style="font-size: 16px; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif;"><u>For Amazon Linux:</u></b><br></p>
<ul>
    <li><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px; font-weight: 700;"><b>First Execute</b> - </span><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;">Automation Document Name:&nbsp;</span>
        <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><b><a href="https://console.aws.amazon.com/systems-manager/automation/execute/AWSDocs-InstallALAMPServer-AL" target="_blank">AWSDocs-InstallALAMPServer-AL</a> ----&gt;&nbsp;</b>Basically Automates - <b><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/install-LAMP.html" target="_blank">this documentation</a>&nbsp;and once the Execution result is "Success"</b></span></font>
    </li>
    <li><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px; font-weight: 700;"><b>Then Execute</b> - </span><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;">Automation Document Name:</span>
        <span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px; font-weight: 700;">&nbsp;</span>
        <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><b><a href="https://console.aws.amazon.com/systems-manager/automation/execute/AWSDocs-HostingAWordPressBlog-AL" target="_blank">AWSDocs-HostingAWordPressBlog-AL&nbsp;</a></b></span></font><span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;">----&gt;&nbsp;</span>
        <span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;">Basically A</span><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;">utomates - <b><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/install-LAMP.html" target="_blank">this documentation</a></b></span></li>
</ul>
<p><b style="font-size: 16px; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif;"><u>For Amazon Linux 2:</u></b><br></p>
<ul>
    <li><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px; font-weight: 700;"><b>First Execute</b> -</span><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px; font-weight: 700;">&nbsp;</span>
        <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;">Automation Document Name:&nbsp;<b> &nbsp;</b></span></font>
        <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><b><a href="https://console.aws.amazon.com/systems-manager/automation/execute/AWSDocs-InstallALAMPServer-AL2" target="_blank">AWSDocs-InstallALAMPServer-AL2</a>&nbsp;</b></span></font><span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;">----&gt; </span>
        <span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;">Basically&nbsp;</span><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;">A</span>
        <span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;">utomates - <b><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-lamp-amazon-linux-2.html" target="_blank">this documentation</a>&nbsp;</b></span>
            <span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;">and once the Execution result is "Success"</span>
    </li>
    <li><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px; font-weight: 700;"><b>Then Execute</b> -</span><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px; font-weight: 700;">&nbsp;</span>
        <span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;">Automation Document Name:</span><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px; font-weight: 700;">&nbsp; &nbsp;</span>
        <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><b><a href="https://console.aws.amazon.com/systems-manager/automation/execute/AWSDocs-HostingAWordPressBlog-AL2" target="_blank">AWSDocs-HostingAWordPressBlog-AL2</a>&nbsp;</b></span></font><span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;">----&gt; </span>
        <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;">Missing a reference as of now for documentation.</span></font>
    </li>
</ul>
<p><br></p>
<p><span style="font-weight: 700; color: rgb(68, 68, 68);"><u style=""><b>Some Important Tips Before you Start:</b></u></span></p>
<p style="margin-top:0cm;margin-right:0cm;margin-bottom:7.5pt;margin-left:0cm"><span style="color: rgb(68, 68, 68); font-weight: 700;">➜</span>
    <font color="#444444" face="Amazon Ember, sans-serif">&nbsp;Please note that these documents may not be available in one of the regions you've targeted. I've checked their presence in - <b>(us-east-1,us-east-2,us-west-1,us-west-2,ca-central-1,eu-central-1,eu-west-1,eu-west-2,eu-west-3,sa-east-1,ap-northeast-1)</b>.
        Please choose your region and proceed.</font>
</p>
<p style="margin-top:0cm;margin-right:0cm;margin-bottom:7.5pt;margin-left:0cm"><span style="color: rgb(68, 68, 68); font-weight: 700;">➜</span><span style="font-family:&quot;Amazon Ember&quot;,sans-serif;mso-bidi-font-family:Arial;
color:#444444">&nbsp;To know more on these documents and what they usually do, you
can click on the <b>Hyperlinks above</b>.<o:p></o:p></span></p>
<p style="margin: 0cm 0cm 7.5pt;"><span style="color: rgb(68, 68, 68); font-weight: 700;">➜</span>
    <font color="#444444" face="Amazon Ember, sans-serif">&nbsp;To run the following Automation documents, <b>you must have permissions to run Automation workflows and create the resources mentioned </b> &nbsp;there. The Automation workflow runs in the context of the current AWS Identity and Access Management (IAM)
        user. <b><i>If you have admin privileges&nbsp;, it will be great</b></i> !
        <o:p></o:p>
    </font>
</p>
<p>



</p>
<p style="margin-top:0cm;margin-right:0cm;margin-bottom:7.5pt;margin-left:0cm"><span style="color: rgb(68, 68, 68); font-weight: 700;">➜</span><span style="font-family:&quot;Amazon Ember&quot;,sans-serif;mso-bidi-font-family:Arial;
color:#444444">&nbsp;You should follow the sequence for executing – <b>1st (“AWSDocs-InstallALAMPServer-AL”
/ “AWSDocs-InstallALAMPServer-AL2”) </b>and then check if <b>“Success”</b>, then you can
Execute <b>2nd (“AWSDocs-HostingAWordPressBlog-AL” / “AWSDocs-HostingAWordPressBlog-AL2”)</b></span></p>
<p style="margin-top:0cm;margin-right:0cm;margin-bottom:7.5pt;margin-left:0cm"><span style="color: rgb(68, 68, 68); font-weight: 700;">➜</span><b style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">&nbsp;</b>
    <font color="#444444" face="Amazon Ember, sans-serif">To track any Progress or Failure, You can navigate to <b><a href="http://console.aws.amazon.com/systems-manager/automation/executions?" target="_blank">SSM Automation Execution</a></b>&nbsp;or <b><a href="http://console.aws.amazon.com/cloudformation/home?#/stacks/" target="_blank">CloudFormation Stack</a></b>        details.&nbsp;</font>
</p>
<p style="margin-top:0cm;margin-right:0cm;margin-bottom:7.5pt;margin-left:0cm"><span style="color: rgb(68, 68, 68); font-weight: 700;">➜</span><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">&nbsp;To delete resources created you can go to&nbsp;</span><span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;"> <b><a href="http://console.aws.amazon.com/cloudformation/home?#/stacks/" target="_blank">CloudFormation Stack</b></a></span>
    <span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">&nbsp;and delete, It will automatically deletes resources.&nbsp;</span>
</p>
<p style="margin-top:0cm;margin-right:0cm;margin-bottom:7.5pt;margin-left:0cm"><span style="color: rgb(68, 68, 68); font-weight: 700;">➜</span><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">&nbsp;You can preserve your resources (to avoid any accidental deletion) using&nbsp;</span><span style="color: rgb(68, 68, 68); font-weight: 700; font-family: &quot;Amazon Ember&quot;, sans-serif;"> <b><a href="http://console.aws.amazon.com/cloudformation/home?#/stacks/" target="_blank">CloudFormation Stack </b></a></span>
    <font color="#444444" face="Amazon Ember, sans-serif" style="color: rgb(68, 68, 68);">&nbsp;by choosing -&nbsp;</font><span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;"><b>"Stack Actions"</b> -&gt; <b>"Edit Termination Protection"</b> --&gt;&nbsp;</span>
    <font color="#444444" face="Amazon Ember, sans-serif" style="color: rgb(68, 68, 68);">Choose&nbsp;</font><span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">- <b>"Enabled"</b> &amp; <b>Save</b></span></p>
<p style="margin-top:0cm;margin-right:0cm;margin-bottom:7.5pt;margin-left:0cm"><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px; font-weight: 700;"><b>------------------------------------------------------------------------------------------------------------------</b></span><br></p>
<p>
    <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif" style="color: rgb(68, 68, 68); font-weight: 700;"><span style="font-size: 16px;"><b><I>Now, we will see how to use&nbsp;</span></font><span style="color: rgb(68, 68, 68); font-weight: 700; font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;">AWS Systems Manager Automation Documents .. I will be taking an Example for "Amazon Linux 2"</b></I></span></p>
<p>
    <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><b>------------------------------------------------------------------------------------------------------------------</b></span></font>
</p>
<ul>
    <li>
        <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif" style=""><span style="color: rgb(68, 68, 68); font-size: 16px; font-weight: 700;"><u><b>Use Case</b></u></span><span style="font-size: 16px;">&nbsp;:-&nbsp; </I><b>"I want to Install LAMP over Amazon Linux 2 based Instance and want to host a WordPress&nbsp;Blog on it</b></I></span></font>
        <span style="color: rgb(68, 68, 68); font-size: 16px; font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif;">"</span>
    </li>
</ul>
<p><br></p>
<p>
    <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><b><u>Steps Using Console:</u></b></span></font>
</p>
<p>
    <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;">As I've mentioned - I will</span></font><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">&nbsp;follow the sequence for executing –&nbsp;</span><span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">1st Doc (“AWSDocs-InstallALAMPServer-AL2”)&nbsp;</span>
    <span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">and then check if&nbsp;</span><span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">“Success”</span>
    <span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">, then will Execute&nbsp;</span>
    <span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">2nd Doc ( “AWSDocs-HostingAWordPressBlog-AL2”)</span>
</p>
<p>
    <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><b>**Note**&nbsp;&nbsp;</b></span></font><b style="font-size: 16px; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif;">Please make sure you're in the right AWS region where you want to deploy your blog.&nbsp;</b></p>
<p>
    <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><b><br></b></span></font>
</p>
<p>
    <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><b>1).</b> Click on below quick-link to Execute&nbsp;</span></font><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif; font-weight: 700;"><b>1st Doc (“AWSDocs-InstallALAMPServer-AL2”)</b> </span>
    <span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">:</span><br></p>
<p>
    <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;">[+] </span></font><b><a href="https://console.aws.amazon.com/systems-manager/automation/execute/AWSDocs-InstallALAMPServer-AL2">https://console.aws.amazon.com/systems-manager/automation/execute/AWSDocs-InstallALAMPServer-AL2</a></b></p>
<p><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image1.JPG" data-filename="image.png" style="width: 836.881px; height: 357.41px;"><b><br></b></p>
<p><span style="color: rgb(68, 68, 68);"><br></span></p>
<p><span style="color: rgb(68, 68, 68);">Once you click on "</span><span style="font-weight: 700; color: rgb(68, 68, 68);"><b>Execute"&nbsp;</span><span style="color: rgb(68, 68, 68);">Button</b> then Automation</span><span style="font-weight: 700; color: rgb(68, 68, 68);">&nbsp;</span>
    <span style="color: rgb(68, 68, 68);">will start and you can see this as follows:</span>
</p>
<p><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image2.JPG" data-filename="image.png" style="width: 812.761px; height: 285.125px;"></p>
<p><span style="color: rgb(68, 68, 68);">You can see the the&nbsp;</span><span style="color: rgb(68, 68, 68);"><b><a href="http://console.aws.amazon.com/cloudformation/home?#/stacks/" target="_blank">CloudFormation&nbsp;Console</a></b> to see what</span>
    <span style="color: rgb(68, 68, 68);">&nbsp;</span><span style="color: rgb(68, 68, 68);">resources are being created by Stack:</span><br></p>
<p><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image3.JPG" style="width: 1049px;"><span style="color: rgb(68, 68, 68);"><br></span><br></p>
<p><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image4.jpg" data-filename="image.png" style="width: 845.08px; height: 522.132px;"><b><br></b></p>
<p><span style="color: rgb(68, 68, 68);">You can Monitor the overall <b>Success </b>in the&nbsp;</span><span style="font-weight: 700; color: rgb(68, 68, 68);">Execution Status&nbsp;</span><span style="color: rgb(68, 68, 68);">under&nbsp;<a href="http://console.aws.amazon.com/systems-manager/automation/executions?" target="_blank"><b>SSM Automation Executions</b></a></span><span style="color: rgb(68, 68, 68);">&nbsp;:</span><b><br></b></p>
<p><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image5.JPG" data-filename="image.png" style="width: 1049px;"><b><br></b></p>
<p><b><br></b></p>
<p><span style="color: rgb(68, 68, 68);"><b>We have an EC2 Instance ready with required configurations:</b></span></p>
<p><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image6.JPG" data-filename="image.png" style="width: 1049px;"><span style="color: rgb(68, 68, 68);"><br></span></p>
<p><br></p>
<p><span style="color: rgb(68, 68, 68);">We've confirmed the&nbsp;</span><span style="font-weight: 700; color: rgb(68, 68, 68);">Execution Status&nbsp;- "</span><span style="color: rgb(68, 68, 68);"><b>Success"&nbsp;</b>for first doc, Now, we can proceed further for our next step..</span><br></p>
<p>
    <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><br></span></font>
</p>
<p>
    <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><span style="font-weight: 700;">2).</span>&nbsp;Click on below quick-link to Execute&nbsp;</span>
    </font><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">&nbsp;</span><span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;"> <b>2nd Doc ( “AWSDocs-HostingAWordPressBlog-AL2”):</b></span></p>
<p><b><font color="#444444" face="Amazon Ember, sans-serif">[+] </font><a href="https://console.aws.amazon.com/systems-manager/automation/execute/AWSDocs-HostingAWordPressBlog-AL2">https://console.aws.amazon.com/systems-manager/automation/execute/AWSDocs-HostingAWordPressBlog-AL2</a></b></p>
<p><b><br></b></p>
<p><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image7.jpg" data-filename="image.png" style="width: 1016.4px; height: 435.045px;">
    <font color="#444444" face="Amazon Ember, sans-serif"><b><br></b></font><br><span style="color: rgb(68, 68, 68);">Once you click on "</span><span style="font-weight: 700; color: rgb(68, 68, 68);"><b>"Execute"</b>&nbsp;</span><span style="color: rgb(68, 68, 68);">Button the&nbsp;Automation</span><span style="font-weight: 700; color: rgb(68, 68, 68);">&nbsp;</span>
    <span style="color: rgb(68, 68, 68);">will start performing actions on your <b><u>Instance</u> </b>you can see this as follows:</span>
</p>
<p><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image8.JPG" data-filename="image.png" style="width: 1049px;"><span style="color: rgb(68, 68, 68);"><br></span></p>
<p><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image9.jpg" data-filename="image.png" style="width: 1011.08px; height: 339.276px;"><span style="color: rgb(68, 68, 68);"><br></span></p>
<p><span style="color: rgb(68, 68, 68);"><br></span></p>
<p><span style="color: rgb(68, 68, 68);">You can Monitor the overall&nbsp;<span style="font-weight: 700;"><b>Success</b>&nbsp;</span>in the&nbsp;</span><span style="font-weight: 700; color: rgb(68, 68, 68);">Execution Status&nbsp;</span><span style="color: rgb(68, 68, 68);">under&nbsp;<span style="font-weight: 700;"><a href="http://console.aws.amazon.com/systems-manager/automation/executions?" target="_blank"><b>SSM Automation Executions</b></a></span><span style="color: rgb(68, 68, 68);">&nbsp;:</span></p>
<p><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image10.JPG" data-filename="image.png" style="width: 1049px;"><br></p>
<p><span style="color: rgb(68, 68, 68);"><br></span></p>
<p><span style="color: rgb(68, 68, 68);"><b> ----------- We've confirmed the&nbsp;</span><span style="font-weight: 700; color: rgb(68, 68, 68);">Execution Status&nbsp;- "</span><span style="color: rgb(68, 68, 68);"><span style="font-weight: 700;">Success"&nbsp;</span>for
    second doc as well, Now, we can proceed further for our next step for final touch on WordPress..</b></span>
</p>
<p><br></p>
<p>
    <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><span style="font-weight: 700;">3).</span>&nbsp;Attached an&nbsp;<b>EIP</b> to the Instance to make sure the IP doesn't change in future. To know more on EIP allocation and Assignment , please refer <b><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html" target="_blank">here</a></b>.</span>
    </font>
</p>
<p><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image11.jpg" data-filename="image.png" style="width: 1049px;">
    <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><br></span></font>
</p>
<p>
    <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><br></span></font>
</p>
<p><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px; font-weight: 700;">4).</span><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;">&nbsp;</span>
    <span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;;">Once the Automation has completed, you will be able to navigate to the WordPress blog dashboard by entering the public DNS address (or the public IP address) of the launched instance in your web browser:</span>
</p>

<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><span style="font-family: &quot;Amazon Ember&quot;; color: rgb(68, 68, 68); background-image: initial; background-position: initial; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;"><b>For example:&nbsp; (in my use-case)</b></span></p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><b>[+]&nbsp;<a href="http://ec2-54-194-131-54.eu-west-1.compute.amazonaws.com/">http://ec2-54-194-131-54.eu-west-1.compute.amazonaws.com/</a>&nbsp; &nbsp; &nbsp;or&nbsp; &nbsp; [+]&nbsp;</b><a href="http://54.194.131.54/" style="background-color: rgb(255, 255, 255);"><b>http://54.194.131.54/</b></a><br></p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><b><br></b></p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal">
    <font color="#444444" face="Amazon Ember">Also, it will automatically&nbsp;route you to <b>"WordPress wp-admin"</b> page which looks like below :</font>
</p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image12.jpg" data-filename="image.png" style="width: 321.08px; height: 356.688px;">
    <font color="#444444" face="Amazon Ember"><br></font>
</p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal">
    <font color="#444444" face="Amazon Ember"><br></font>
</p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal">
    <font color="#444444" face="Amazon Ember">Click <b>Continue </b>and&nbsp;</font><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;;">&nbsp;</span><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;;">Just fill in
the information below and you’ll be on your way to using wordpress to manage your blog :</span></p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image13.jpg" data-filename="image.png" style="width: 429.271px; height: 463.34px;"><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;;"><br></span></p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><br></p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;;">Please make a note of <b>username&nbsp;</b></span><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;;">and <b>password </b>to manage your WordPress blog. Click on <b>"Install WordPress" </b>b</span>
    <span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;;">utton.</span>
</p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image14.jpg" data-filename="image.png" style="width: 424.08px; height: 225.38px;"><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;;"><br></span></p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;;">Click L<b>ogin</b>&nbsp;and use the Id and Password provided above :<br></span></p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image15.jpg" data-filename="image.png" style="width: 296px;"><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;;"><br></span></p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;;">Here is the <b>WordPress Dashboard </b>to manage you Blog:</span></p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image16.jpg" data-filename="image.png" style="width: 1049px;"><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;;"><br></span></p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;;"><br></span></p>
<p class="MsoNormal" style="margin-bottom: 7.5pt; line-height: normal;"><span style="font-family: &quot;Amazon Ember&quot;; color: rgb(68, 68, 68); background-image: initial; background-position: initial; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;"><span style="font-weight: 700;">Checking my blog created :</span></span>
</p>
<p class="MsoNormal" style="margin-bottom: 7.5pt; line-height: normal;"><span style="font-weight: 700;">[+]&nbsp;<a href="http://ec2-54-194-131-54.eu-west-1.compute.amazonaws.com/">http://ec2-54-194-131-54.eu-west-1.compute.amazonaws.com/</a>&nbsp; &nbsp; &nbsp;or&nbsp; &nbsp; [+]&nbsp;</span>
    <span style="background-color: rgb(255, 255, 255); font-weight: 700;"><a href="http://54.194.131.54/" style="background-color: rgb(255, 255, 255);">http://54.194.131.54/</a></span><br></p>
<div><br></div>
<div><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image17.jpg" data-filename="image.png" style="width: 848.966px; height: 388.469px;"><br></div>
<div><br></div>
<div><br></div>
<div><br></div>
<div><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;"><b>&lt;&lt; To delete the Resources created &gt;&gt;</b></span><br></div>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><span style="color: rgb(68, 68, 68); font-weight: 700;">➜</span><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">&nbsp;To delete resources created you can go to&nbsp;</span><span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;"><a href="http://console.aws.amazon.com/cloudformation/home?#/stacks/" target="_blank"><b>CloudFormation Stack</b></a></span>
    <span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">&nbsp;and Select your Stack and choose <b>"Delete"</b>, It will automatically deletes resources.&nbsp;</span>
</p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image18.jpg" data-filename="image.png" style="width: 760.969px; height: 240.115px;">
    <span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;"><br></span>
</p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;"><br></span></p>
<div><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;"><span style="font-weight: 700;">&lt;&lt; <b>--------To preserve the Resources created / Avoid Accidental deletion--------------</b> &gt;&gt;</span></span>
</div>
<div>
    <p class="MsoNormal" style="margin-bottom: 7.5pt; line-height: normal;"><span style="color: rgb(68, 68, 68); font-weight: 700;">➜</span><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">&nbsp;You can go to&nbsp;</span><span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;"><a href="http://console.aws.amazon.com/cloudformation/home?#/stacks/" target="_blank"><b>CloudFormation Stack</b></a></span>
        <font color="#444444" face="Amazon Ember, sans-serif">&nbsp;and Select your Stack and choose - </font><b style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">"Stack Actions" -&gt; "Edit Termination Protection" --&gt; </b>
        <font color="#444444" face="Amazon Ember, sans-serif">Choose </font><b style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">- "Enabled" &amp; Save</b></p>
    <p class="MsoNormal" style="margin-bottom: 7.5pt; line-height: normal;"><b style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;"><br></b>
        <font color="#444444" face="Amazon Ember, sans-serif">This will basically will avoid your resources being deleted accidentally by CloudFormation action. To know more on this, please check our <b><a href="https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-protect-stacks.html?icmpid=docs_cfn_console" target="_blank">Public Documentation.</a></b></font>
    </p>
    <p class="MsoNormal" style="margin-bottom: 7.5pt; line-height: normal;">
        <font color="#444444" face="Amazon Ember, sans-serif"><b><br></b></font>
    </p>
    <p class="MsoNormal" style="margin-bottom: 7.5pt; line-height: normal;"><https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image19.jpg" data-filename="image.png" style="width: 1049px;"><br></p>
</div>
<div><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;"><span style="font-weight: 700;"><br></span></span><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image20.jpg" data-filename="image.png" style="width: 453px;"></div>
<div><br></div>
<div><img src="https://github.com/dineshrathee12/SSM_Automation_AWSDocs-InstallALAMPServer_-_AWSDocs-HostingAWordPressBlog/blob/master/Images/Image21.jpg" data-filename="image.png" style="width: 907px;"><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;"><span style="font-weight: 700;"><br></span></span>
</div>
<div><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;"><span style="font-weight: 700;"><br></span></span>
</div>
<div><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;"><span style="font-weight: 700;"><br></span></span>
</div>
<div><br></div>
<div><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;"><span style="font-weight: 700;"><br></span></span>
</div>
<div><span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;"><u><b>========= LPerforming above Steps Using AWS CLI ================ </b></u></span></div>
<div><span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;"><u><br></u></span></div>
<div><span style="color: rgb(68, 68, 68); font-weight: 700; font-size: 16px;"><font face="Amazon Ember, Helvetica, Arial, sans-serif">1). <b>Running 1st</b>&nbsp;</font></span><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif; font-weight: 700;"><b>Doc (“AWSDocs-InstallALAMPServer-AL2”)</b>&nbsp;</span>
    <span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">:</span>
</div>
<div><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;"><br></span></div>
<div><pre style=""><font color="#444444" face="Amazon Ember, sans-serif"># aws ssm <b>start-automation-execution</b> --document-name <b>"AWSDocs-InstallALAMPServer-AL2" </b>--document-version "\$DEFAULT" <b>--region eu-west-1</b><br></font><font color="#444444" face="Amazon Ember, sans-serif">{<br></font><font color="#444444" face="Amazon Ember, sans-serif">&nbsp; &nbsp; "AutomationExecutionId": <b>"bd56b368-1a52-43e8-ac53-c0fd9175a599"</b><br></font><font color="#444444" face="Amazon Ember, sans-serif">}</font></pre><br></div>
<div><span style="color: rgb(68, 68, 68); font-weight: 700;">-&nbsp;</span><span style="color: rgb(68, 68, 68); font-weight: 700;"><b>Checking the Automation progress</b>&nbsp;</span><span style="color: rgb(68, 68, 68); font-weight: 700;"><b>/ Status:</b></span></div>
<div><span style="color: rgb(68, 68, 68); font-weight: 700;"><br></span></div>
<div><pre style=""><font color="#444444"># aws ssm <b>get-automation-execution</b> --automation-execution-id <b>"bd56b368-1a52-43e8-ac53-c0fd9175a599"</b> <b>--region eu-west-1</b> --output text --query "AutomationExecution.AutomationExecutionStatus"<br></font><font color="#444444"><b>InProgress</b></font></pre>
    <span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, Helvetica, Arial, sans-serif; font-size: 16px;"><u><br></u></span>
</div>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal">
    <o:p></o:p>
</p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><span style="font-weight: 700; color: rgb(68, 68, 68);"><b>- Lets wait for few mins to get this completed and Can check the Status again:</b></span></p><pre style="margin-bottom:7.5pt;line-height:normal"><font color="#444444"># aws ssm <b>get-automation-execution</b> --automation-execution-id <b>"bd56b368-1a52-43e8-ac53-c0fd9175a599"</b> <b>--region eu-west-1 -</b>-output text --query "AutomationExecution.AutomationExecutionStatus"<br></font><font color="#444444"><b>Success</b></font></pre>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><span style="font-weight: 700; color: rgb(68, 68, 68);"><br></span></p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><span style="font-weight: 700; color: rgb(68, 68, 68);"><b>- You can also check the CloudFormation Stack details/Status :</b></span></p><pre style="margin-bottom:7.5pt;line-height:normal"><font color="#444444"><b># </b>aws cloudformation <b>describe-stacks </b>--stack-name <b>"LAMPStack-AL2" </b>--region eu-west-1</font></pre>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><span style="font-weight: 700; color: rgb(68, 68, 68);"><br></span></p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><span style="font-weight: 700; color: rgb(68, 68, 68);">-&nbsp;</span><span style="color: rgb(68, 68, 68); font-weight: 700;"><b>To define CloudFormation stack resources :</b></span></p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"></p><pre><font color="#444444"># aws cloudformation <b>describe-stack-resources&nbsp;</b> --stack-name <b>"LAMPStack-AL2"</b> --region eu-west-1</font></pre>
<font color="#444444" face="Amazon Ember"><b><br></b></font>
<p></p>
<p><span style="color: rgb(68, 68, 68);">We've confirmed the&nbsp;</span><span style="font-weight: 700; color: rgb(68, 68, 68);">Execution Status&nbsp;- "</span><span style="color: rgb(68, 68, 68);"><span style="font-weight: 700;"><b>Success</b>"&nbsp;</span>for
    first doc as well as CloudFormation stack status &amp; resources, Now, we can proceed further for our next step..</span>
</p>
<p><br></p>
<p>
    <font color="#444444" face="Amazon Ember, Helvetica, Arial, sans-serif"><span style="font-size: 16px;"><span style="font-weight: 700;">2).</span>&nbsp;<b>Running</b></span>
    </font><span style="font-weight: 700; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">&nbsp;<b>2nd Doc ( “AWSDocs-HostingAWordPressBlog-AL2”) :</b></span></p><pre style="margin-bottom:7.5pt;line-height:normal"><font color="#444444" face="Amazon Ember"># aws ssm <b>start-automation-execution </b>--document-name <b>"AWSDocs-HostingAWordPressBlog-AL2"</b> --document-version "\$DEFAULT" <b>--region eu-west-1<br></b></font><font color="#444444" face="Amazon Ember">{<br></font><font color="#444444" face="Amazon Ember">&nbsp; &nbsp; "AutomationExecutionId": <b>"d61b49b7-1e36-488b-ba58-852f603dd373"<br></b></font><font color="#444444" face="Amazon Ember">}</font></pre>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"></p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal">
    <font color="#444444" face="Amazon Ember"><br></font><span style="color: rgb(68, 68, 68); font-weight: 700;">- Lets wait for few mins to get this completed and Can check the Status :</span></p><pre style="margin-bottom:7.5pt;line-height:normal"># aws ssm <b>get-automation-execution</b> --automation-execution-id <b>"d61b49b7-1e36-488b-ba58-852f603dd373" </b>--region <b>eu-west-1</b> --output text --query "AutomationExecution.AutomationExecutionStatus"<br><b>Success</b></pre>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><br><span style="font-size:
12.0pt;font-family:&quot;Times New Roman&quot;,serif;mso-fareast-font-family:&quot;Times New Roman&quot;;
mso-fareast-language:EN-GB"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin-bottom:7.5pt;line-height:normal"><span style="font-family: &quot;Amazon Ember&quot;; color: rgb(68, 68, 68); background-image: initial; background-position: initial; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;"><o:p></o:p></span></p>
<p>
    <font color="#444444"><b>You can read more on AWS CLI references here :</b></font>
</p>
<p><b><font color="#444444">[+] SSM AWS CLI References :&nbsp;</font><a href="https://docs.aws.amazon.com/cli/latest/reference/ssm/index.html#cli-aws-ssm">https://docs.aws.amazon.com/cli/latest/reference/ssm/index.html#cli-aws-ssm</a><a href="https://docs.aws.amazon.com/cli/latest/reference/ssm/index.html#cli-aws-ssm"></a></b></p>
<p><b><font color="#444444" style="">[+] CloudFormation AWS CLI References :&nbsp;</font></b><a href="https://docs.aws.amazon.com/cli/latest/reference/cloudformation/index.html#cli-aws-cloudformation"><b>https://docs.aws.amazon.com/cli/latest/reference/cloudformation/index.html#cli-aws-cloudformation</b></a><b><a href="https://docs.aws.amazon.com/cli/latest/reference/cloudformation/index.html#cli-aws-cloudformation" style=""></a></b></p>
<p><br></p>
<p><u style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif; font-weight: 700;">Some other references to check&nbsp;</u><span style="color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif; font-weight: 700;">:</span><br></p>
<p>
    <font color="#444444" face="Amazon Ember, sans-serif" style="font-weight: bold;">[+] Tutorials for Amazon EC2 Instances Running Linux: </font><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-tutorials.html" style="">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-tutorials.html</a></p>
<p><span style="font-weight: bold; color: rgb(68, 68, 68); font-family: &quot;Amazon Ember&quot;, sans-serif;">[+] Tutorial: Install a LAMP Web Server with the Amazon Linux AMI: </span><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/install-LAMP.html" style="">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/install-LAMP.html</a><br></p>
<p>
    <font color="#444444" face="Amazon Ember, sans-serif" style="font-weight: bold;">[+] AWSDocs-InstallALAMPServer-AL : </font><a href="https://eu-west-1.console.aws.amazon.com/systems-manager/automation/execute/AWSDocs-InstallALAMPServer-AL?region=eu-west-1" style="background-color: rgb(255, 255, 255);">https://eu-west-1.console.aws.amazon.com/systems-manager/automation/execute/AWSDocs-InstallALAMPServer-AL?region=eu-west-1</a><br></p>
<p>
    <font color="#444444" face="Amazon Ember, sans-serif" style="font-weight: bold;">[+] Tutorial: Hosting a WordPress Blog with Amazon Linux : </font><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/hosting-wordpress.html" style="background-color: rgb(255, 255, 255);">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/hosting-wordpress.html</a><br></p>
<p>
    <font color="#444444" face="Amazon Ember, sans-serif" style="font-weight: bold;">[+] AWSDocs-HostingAWordPressBlog-AL : </font><a href="https://console.aws.amazon.com/systems-manager/automation/execute/AWSDocs-HostingAWordPressBlog-AL" style="background-color: rgb(255, 255, 255);">https://console.aws.amazon.com/systems-manager/automation/execute/AWSDocs-HostingAWordPressBlog-AL</a><br></p>
<p><br></p>
<p>
    <font color="#444444" face="Amazon Ember, sans-serif" style="font-weight: bold;">[+] Tutorial: Install a LAMP Web Server on Amazon Linux 2: </font><a href="https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-lamp-amazon-linux-2.html" style="">https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-lamp-amazon-linux-2.html</a></p>
<p>
    <font color="#444444" face="Amazon Ember, sans-serif" style="font-weight: bold;">[+] AWSDocs-InstallALAMPServer-AL2 : </font><a href="https://eu-west-1.console.aws.amazon.com/systems-manager/home?redirect=%2Fsystems-manager%2Fautomation%2Fexecute%2FAWSDocs-InstallALAMPServer-AL2&amp;region=eu-west-1" style="background-color: rgb(255, 255, 255);">https://eu-west-1.console.aws.amazon.com/systems-manager/home?redirect=%2Fsystems-manager%2Fautomation%2Fexecute%2FAWSDocs-InstallALAMPServer-AL2®ion=eu-west-1</a><br></p>
<p>
    <font color="#444444" face="Amazon Ember, sans-serif" style="font-weight: bold;">[+] AWSDocs-HostingAWordPressBlog-AL2 : </font><a href="https://console.aws.amazon.com/systems-manager/home?redirect=%2Fsystems-manager%2Fautomation%2Fexecute%2FAWSDocs-HostingAWordPressBlog-AL2" style="background-color: rgb(255, 255, 255);">https://console.aws.amazon.com/systems-manager/home?redirect=%2Fsystems-manager%2Fautomation%2Fexecute%2FAWSDocs-HostingAWordPressBlog-AL2</a><br></p>
<p><br></p>
<p><b>[+] Troubleshooting AWS CloudFormation </b>: <a href="https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/troubleshooting.html">https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/troubleshooting.html</a></p>
<p><b>[+] Troubleshooting Systems Manager Automation:</b> <a href="https://docs.aws.amazon.com/systems-manager/latest/userguide/automation-troubleshooting.html">https://docs.aws.amazon.com/systems-manager/latest/userguide/automation-troubleshooting.html</a></p>
<p><b>[+] WordPress :</b> <a href="https://wordpress.com/start/?ref=create-lp">https://wordpress.com/start/?ref=create-lp</a>
    <a href="https://tiny.amazon.com/olzpp33h/googpageaclk"></a>
</p>
<p><br></p>
<p><span style="color: rgb(68, 68, 68); font-weight: 700;">Thanks for reading. Will experiment more scenarios in future and will keep you posted :)&nbsp;</span><br></p>
