all: clean generate

generate:
	ocarina -aadlv2 -f -b -r producer_consumer::pc.varimpl -g polyorb_hi_c *.aadl
	ocarina -aadlv2 -f -b -r producer_consumer::pc.flowimpl -g polyorb_hi_c *.aadl

clean:
	rm -rf *~ pc_flowimpl pc_varimpl
