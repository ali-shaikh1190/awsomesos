# DC/OS 1.9 Multi AZ with EFS CloudFormation Template

You can create a DC/OS cluster for Amazon Web Services (AWS) by using the DC/OS templates on AWS CloudFormation.

## Template
The Following Template creates a Stable DC/OS 1.9 Stack with EFS Mounted on public and private nodes.

<table width="100%">
    <tr>
        <th align="left" colspan="2"><h4><a href="https://github.com/ali-shaikh1190/awsomesos/blob/master/cloudformation/multi-master-multi-az-efs.yaml">Infrastructure</a></h4></th>
    </tr>
    <tr>
        <td>
            <h6>Create Details</h6>
            <ol>
             <li>VPC</li>
             <li>3 Public Subnets</li>
             <li>3 Private Subnet's with Nat GW Attached</li>
             <li>EFS with 3 mount Target's in Private Subnet's</li>
             <li> Default 3 Master Nodes Configured in Publc Seubnet</li>
             <li> Default 1 Public Slave Node Configured in Publc Subnet</li>
             <li> Default 1 Private Node Configured in Private Subnet</li>
             <li> Default Instance Type m3.xlarge</li>
             <li> CoreOS AMI</li>
             </ol>
          </td>
   </tr>
 </table>
 
<table width="100%">
          <tr>
            <td nowrap width="200" valign="top">
            </tr>
                <tr>
                    <th align="left">Launch</th>
                </tr>
                <tr>
                    <td>
                        <a href="https://console.aws.amazon.com/cloudformation/home?#/stacks/new?&templateURL=https://github.com/ali-shaikh1190/awsomesos/blob/master/cloudformation/multi-master-multi-az-efs.yaml" target="_blank"><img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"></a>
                    </td>
                </tr >
            
           <td nowrap width="200" valign="top">
                <tr>
                    <th align="left">View in Designer</th>
                </tr>
                <tr>
                    <td nowrap width="200">
                        <a href="https://console.aws.amazon.com/cloudformation/designer/home?region=useast-1&templateURL=https://github.com/ali-shaikh1190/awsomesos/blob/master/cloudformation/multi-master-multi-az-efs.yaml" target="_blank"><img src="https://s3-ap-southeast-1.amazonaws.com/uploads-ap.hipchat.com/6719/959520/BSe6syEHbZP8Yhw/template1-designer.png" width:40% alt="View in Designer"></a>
                    </td>
               </tr>
</table>


