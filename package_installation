node  'puppet-agent.example.com' {

        file {  '/etc/motd':
        content => "this is via puppet master \n",
        }
        
        package { 'vsftpd':
        ensure=>present,
        }
        
        user { 'ironman':
        ensure => present,
        comment => 'iron man ',
        home => '/home/ironman',
        managehome => true,
        password => 'kkdfjkkljkasjdkjoo9089793lasdalkmmmmmmmm',
        }
        
}
          
        
