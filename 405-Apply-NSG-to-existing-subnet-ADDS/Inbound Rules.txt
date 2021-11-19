{
                        "name": "Allow-adds-outb-adds-dns-Tcp",
                        "properties": {
                            "protocol": "Tcp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "53",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "access": "Allow",
                            "priority": 1000,
                            "direction": "Outbound"
                        }
                    },
                    {
                        "name": "Allow-adds-outb-adds-dns-Udp",
                        "properties": {
                            "protocol": "Udp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "53",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "access": "Allow",
                            "priority": 1005,
                            "direction": "Outbound"
                        }
                    },
                    {
                        "name": "Allow-adds-outb-adds-krbtckt-Tcp",
                        "properties": {
                            "protocol": "Tcp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "88",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "access": "Allow",
                            "priority": 1010,
                            "direction": "Outbound"
                        }
                    },
                    {
                        "name": "Allow-adds-outb-adds-krbtckt-Udp",
                        "properties": {
                            "protocol": "Udp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "88",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "access": "Allow",
                            "priority": 1015,
                            "direction": "Outbound"
                        }
                    },
                    {
                        "name": "Allow-adds-outb-adds-ntptime-Udp",
                        "properties": {
                            "protocol": "Udp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "123",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "access": "Allow",
                            "priority": 1020,
                            "direction": "Outbound"
                        }
                    },
                    {
                        "name": "Allow-adds-outb-adds-rpcmapper-Tcp",
                        "properties": {
                            "protocol": "Tcp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "135",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "access": "Allow",
                            "priority": 1025,
                            "direction": "Outbound"
                        }
                    },
                    {
                        "name": "Allow-adds-outb-adds-ldap-Tcp",
                        "properties": {
                            "protocol": "Tcp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "389",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "access": "Allow",
                            "priority": 1030,
                            "direction": "Outbound"
                        }
                    },
                    {
                        "name": "Allow-adds-outb-adds-ldap-Udp",
                        "properties": {
                            "protocol": "Udp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "389",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "access": "Allow",
                            "priority": 1035,
                            "direction": "Outbound"
                        }
                    },
                    {
                        "name": "Allow-adds-outb-adds-smb-Tcp",
                        "properties": {
                            "protocol": "Tcp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "445",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "access": "Allow",
                            "priority": 1040,
                            "direction": "Outbound"
                        }
                    },
                    {
                        "name": "Allow-adds-outb-adds-smb-Udp",
                        "properties": {
                            "protocol": "Udp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "445",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "access": "Allow",
                            "priority": 1045,
                            "direction": "Outbound"
                        }
                    },
                    {
                        "name": "Allow-adds-outb-adds-krbpasswd-Tcp",
                        "properties": {
                            "protocol": "Tcp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "464",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "access": "Allow",
                            "priority": 1050,
                            "direction": "Outbound"
                        }
                    },
                    {
                        "name": "Allow-adds-outb-adds-krbpasswd-Udp",
                        "properties": {
                            "protocol": "Udp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "464",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "access": "Allow",
                            "priority": 1055,
                            "direction": "Outbound"
                        }
                    },
                    {
                        "name": "Allow-adds-outb-adds-ldapssl-Tcp",
                        "properties": {
                            "protocol": "Tcp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "636",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "access": "Allow",
                            "priority": 1060,
                            "direction": "Outbound"
                        }
                    },
                    {
                        "name": "Allow-adds-outb-adds-gc-Tcp",
                        "properties": {
                            "protocol": "Tcp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "3268",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "access": "Allow",
                            "priority": 1065,
                            "direction": "Outbound"
                        }
                    },
                    {
                        "name": "Allow-adds-outb-adds-gcssl-Tcp",
                        "properties": {
                            "protocol": "Tcp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "3269",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "access": "Allow",
                            "priority": 1070,
                            "direction": "Outbound"
                        }
                    },
                    {
                        "name": "Allow-adds-outb-adds-dfsr-Tcp",
                        "properties": {
                            "protocol": "Tcp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "5722",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "access": "Allow",
                            "priority": 1075,
                            "direction": "Outbound"
                        }
                    },

                    {
                        "name": "Allow-adds-outb-adds-rpcdynamic-Tcp",
                        "properties": {
                            "protocol": "Tcp",
                            "sourcePortRange": "*",
                            "destinationPortRange": "49152-65535",
                            "sourceAddressPrefix": "[parameters('nsgAddsSubnet')]",
                            "destinationAddressPrefixes": [
                                "[parameters('nsgAddsSubnet')]",
                                "[parameters('nsgBizSubnet')]",
                                "[parameters('nsgBizTestSubnet')]",
                                "[parameters('nsgDataSubnet')]",
                                "[parameters('nsgCtxInfSubnet')]",
                                "[parameters('nsgCtxAppSubnet')]"
                            ],
                            "access": "Allow",
                            "priority": 1080,
                            "direction": "Outbound"
                        }
                    },
                    