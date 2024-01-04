+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ now.Format (default "2006-01-02 15:04:05" .Site.Params.dateFmt) }}
draft = true
categories = ['c1', 'c2']
tags = ['t1', 't2']
+++