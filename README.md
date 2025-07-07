# WebDocumentCrawler
A smart and efficient web-based tool designed to automatically crawl, extract, and organize documents from targeted websites. This application helps users gather publicly available PDFs, DOCX, and other file types for research, compliance checks, content indexing, or threat intelligence. With customizable filters, keyword targeting, and metadata extraction, Web Document Crawler streamlines the process of finding and analyzing relevant web documents, saving time and enhancing productivity for analysts, researchers, and security professionals.

#Runtime & Software Dependencies
Software	Required Version	Notes
1. Java JDK version 24

#Path in Windows  
@echo off
set DIR=%~dp0
echo DIR = %DIR%
echo Running Java with classpath:
echo %DIR%WebDocumentCrawlerApp.jar;%DIR%lib\jsoup-1.21.1.jar

java -cp "%DIR%WebDocumentCrawlerApp.jar;%DIR%lib\jsoup-1.21.1.jar" crawler.WebDocumentCrawlerApp
pause

#System Requirements
Component	Minimum	Recommended
CPU	Dual-core 2.0 GHz	Quad-core 2.5 GHz+
RAM	2 GB
Storage	2 GB free space	50 GB+ for large document sets
Display	1280x720 resolution	1920x1080 Full HD
Network	Internet connection required for external crawling	

