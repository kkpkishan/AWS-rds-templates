# AWS MySql RDS CloudFormation Templates
<table width="100%">
    <tr>
        <th align="left" colspan="2"><h4><a href="https://github.com/kkpkishan/aws-mysql-rds-cloudformation-templates/blob/master/mysql-rds.yml">MySQL RDS</a></h4></th>
    </tr>
    <tr>
        <td width="100%" valign="top">
           <p>Creates a MySQL RDS Database Instance.</p>
           <h6>Prerequisites</h6>
           <ol>
            <li>VPC</li>
            <ul>
              <li>Public Subnet, IGW, Private Subnet/s.</li>
              <li>Either use an existing VPC Infrastructure or you can use the following <a href="https://github.com/kkpkishan/aws-vpc-cloudformation-Templates/blob/master/vpc.yml" target="_blank">VPC Template</a> to create a one.</li>
            </ul>
           </ol>
           <h6>Create Details</h6>
           <ol>
            <li>DB Instance</li>
            <li>DB Subnet Group</li>
            <li>Security Group</li>
            <li>Cloud Watch Alarms</li>
            <li>Route 53 Record Set (Optional)</li>
           </ol>
        </td>
        <td nowrap width="200" valign="top">
            <table>
                <tr>
                    <th align="left">Launch</th>
                </tr>
                <tr>
                    <td>
                        <a href="https://console.aws.amazon.com/cloudformation/home?#/stacks/new?&templateURL=https://electromech-cloudformation-templates.s3.ap-south-1.amazonaws.com/mysql-rds.yml" target="_blank"><img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"></a>
                    </td>
                </tr>
            </table>
        </td>
    </tr>
</table>

