benchmarks = mysql2 new-parser

include ../common.mk


#SHELL := /bin/bash

#benchmarks = poc mysql2
#tsv_files = $(addprefix results/,$(addsuffix .tsv,$(benchmarks)))
#fixtures = benchmark/fixtures/100k-blog-rows.mysql
#png_files = $(subst pdf,png,$(wildcard pdfs/*.pdf))

#all: pdfs pngs tsvs fixtures

#fixtures: $(fixtures)

#tsvs: $(tsv_files)

#$(tsv_files): results/%.tsv: benchmark/%/run.js
	#./$^ | tee $@

#$(fixtures):
	#curl -z '$@' -o '$@' 'http://felixge.s3.amazonaws.com/12/`basename $@`'

#pdfs: $(tsv_files)
	#cd pdfs && ./generate.r

#pngs: $(png_files)

#$(png_files): pngs/%.png: pdfs/%.pdf
	#convert -density 300 $^ -resize 1024x $@

#.PHONY: all fixtures pdfs pngs tsvs
