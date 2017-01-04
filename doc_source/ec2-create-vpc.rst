.. Copyright 2010-2016 Amazon.com, Inc. or its affiliates. All Rights Reserved.

   This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0
   International License (the "License"). You may not use this file except in compliance with the
   License. A copy of the License is located at http://creativecommons.org/licenses/by-nc-sa/4.0/.

   This file is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
   either express or implied. See the License for the specific language governing permissions and
   limitations under the License.

.. _aws-ruby-sdk-ec2-create-vpc:

Creating a VPC
======================================

The following example creates the virtual private cloud (VPC) :code:`MyGroovyVPC` with the CIDR block :code:`10.200.0.0/16`, and then displays the VPC's ID.

The example creates a virtual network with 65,536 private IP addresses.

.. literalinclude:: ./example_code/ec2/ec2-ruby-example-create-vpc.rb
   :lines: 13-31
   :dedent: 0
   :language: ruby