import React, { useMemo, useState } from "react";
import { motion } from "framer-motion";
import { Check, LineChart, Users, Wallet, Sparkles, Shield, ArrowRight, Calculator, FileText } from "lucide-react";
import { Button } from "@/components/ui/button";
import { Card, CardContent, CardHeader, CardTitle } from "@/components/ui/card";
import { Input } from "@/components/ui/input";
import { Slider } from "@/components/ui/slider";

export default function ClippersLanding() {
  // Earnings calculator state
  const [views, setViews] = useState(100000);
  const [rate, setRate] = useState(1.25); // $ per 1k views default midpoint

  const earnings = useMemo(() => ((views / 1000) * rate).toFixed(2), [views, rate]);

  const features = [
    { icon: Users, title: "Free community", desc: "Join a private hub of editors with live jobs, resources, and support." },
    { icon: Shield, title: "Standards that protect you", desc: "Clear brand rules, export specs, and QC so your work passes first try." },
    { icon: Wallet, title: "Transparent payouts", desc: "$0.50 to $2.00 per 1,000 views with minimums and bonuses." },
    { icon: LineChart, title: "Real growth", desc: "Work with creators who publish consistently and want long term partners." },
  ];

  const steps = [
    { title: "Apply and join", desc: "Enter the free community and complete a short profile." },
    { title: "Review standards", desc: "Skim the style rules and export specs. Optional skill refreshers available." },
    { title: "Get matched", desc: "We route briefs from creators that fit your style and niche." },
    { title: "Deliver and get paid", desc: "Submit your edit, pass QC, track views, and receive payouts." },
  ];

  return (
    <div className="min-h-screen bg-white text-gray-900">
      {/* Hero */}
      <section className="relative overflow-hidden">
        <div className="absolute inset-0 bg-gradient-to-b from-blue-50/60 to-white pointer-events-none" />
        <div className="mx-auto max-w-7xl px-6 pt-16 pb-10">
          <div className="grid lg:grid-cols-2 gap-10 items-center">
            <motion.div initial={{ opacity: 0, y: 20 }} animate={{ opacity: 1, y: 0 }} transition={{ duration: 0.6 }}>
              <h1 className="text-4xl md:text-5xl font-semibold tracking-tight">
                Connect with creators. Clip. Get paid.
              </h1>
              <p className="mt-4 text-lg text-gray-700 max-w-prose">
                Scale Suite matches experienced clippers with creators. Join free, follow clear standards, and earn per view with transparent rates and guaranteed minimums.
              </p>
              <div className="mt-6 flex flex-wrap items-center gap-3">
                <Button size="lg" className="rounded-2xl px-6">
                  Join free community
                </Button>
                <Button variant="outline" size="lg" className="rounded-2xl px-6">
                  See open gigs <ArrowRight className="ml-2 h-4 w-4" />
                </Button>
              </div>
              <div className="mt-6 flex items-center gap-2 text-sm text-gray-600">
                <Sparkles className="h-4 w-4" /> <span>No fees to join. Keep your own edits and workflows.</span>
              </div>
            </motion.div>

            {/* Calculator */}
            <motion.div initial={{ opacity: 0, y: 20 }} animate={{ opacity: 1, y: 0 }} transition={{ duration: 0.6, delay: 0.1 }}>
              <Card className="rounded-2xl shadow-xl">
                <CardHeader>
                  <CardTitle className="flex items-center gap-2"><Calculator className="h-5 w-5" /> Earnings calculator</CardTitle>
                </CardHeader>
                <CardContent className="space-y-6">
                  <div>
                    <label className="text-sm font-medium">Views</label>
                    <div className="mt-2 flex items-center gap-3">
                      <Input
                        type="number"
                        value={views}
                        onChange={(e) => setViews(Math.max(0, Number(e.target.value)))}
                        className="rounded-xl"
                      />
                      <span className="text-sm text-gray-500">per clip</span>
                    </div>
                    <div className="mt-3">
                      <Slider value={[views]} min={0} max={2000000} step={1000} onValueChange={(v) => setViews(v[0])} />
                    </div>
                  </div>

                  <div>
                    <label className="text-sm font-medium">Rate per 1,000 views</label>
                    <div className="mt-2 flex items-center gap-3">
                      <Input
                        type="number"
                        step="0.05"
                        value={rate}
                        onChange={(e) => setRate(Math.max(0.25, Number(e.target.value)))}
                        className="rounded-xl"
                      />
                      <span className="text-sm text-gray-500">USD</span>
                    </div>
                    <div className="mt-3">
                      <Slider value={[rate]} min={0.50} max={3} step={0.05} onValueChange={(v) => setRate(v[0])} />
                    </div>
                  </div>

                  <div className="rounded-xl bg-blue-50 p-4">
                    <p className="text-sm text-gray-600">Estimated payout</p>
                    <p className="mt-1 text-3xl font-semibold">${earnings}</p>
                    <p className="mt-1 text-xs text-gray-500">Based on {views.toLocaleString()} views at ${rate.toFixed(2)} CPM</p>
                  </div>

                  <ul className="text-sm text-gray-600 space-y-2">
                    <li className="flex items-start gap-2"><Check className="h-4 w-4 mt-0.5" /> Minimum payout per approved clip so you never earn zero</li>
                    <li className="flex items-start gap-2"><Check className="h-4 w-4 mt-0.5" /> Bonuses for strong retention and fast turnarounds</li>
                    <li className="flex items-start gap-2"><Check className="h-4 w-4 mt-0.5" /> View window tracked and verified</li>
                  </ul>
                </CardContent>
              </Card>
            </motion.div>
          </div>
        </div>
      </section>

      {/* Why join */}
      <section className="mx-auto max-w-7xl px-6 py-14">
        <div className="grid md:grid-cols-4 gap-6">
          {features.map((f, i) => (
            <motion.div key={i} initial={{ opacity: 0, y: 10 }} whileInView={{ opacity: 1, y: 0 }} viewport={{ once: true }} transition={{ duration: 0.4, delay: i * 0.05 }}>
              <Card className="h-full rounded-2xl">
                <CardHeader>
                  <CardTitle className="flex items-center gap-2 text-lg"><f.icon className="h-5 w-5" />{f.title}</CardTitle>
                </CardHeader>
                <CardContent>
                  <p className="text-gray-600 text-sm">{f.desc}</p>
                </CardContent>
              </Card>
            </motion.div>
          ))}
        </div>
      </section>

      {/* How it works */}
      <section className="mx-auto max-w-7xl px-6 py-14">
        <div className="grid lg:grid-cols-2 gap-10 items-start">
          <div>
            <h2 className="text-3xl font-semibold">How it works</h2>
            <p className="mt-3 text-gray-700 max-w-prose">Focused on experienced clippers. We keep training optional and standards mandatory so every delivery is consistent and fair.</p>
            <div className="mt-8 space-y-6">
              {steps.map((s, i) => (
                <div key={i} className="flex items-start gap-4">
                  <div className="h-10 w-10 rounded-2xl bg-blue-100 flex items-center justify-center font-semibold">{i + 1}</div>
                  <div>
                    <h3 className="font-medium">{s.title}</h3>
                    <p className="text-sm text-gray-600">{s.desc}</p>
                  </div>
                </div>
              ))}
            </div>
          </div>

          {/* Rates table */}
          <Card className="rounded-2xl">
            <CardHeader>
              <CardTitle className="flex items-center gap-2"><Wallet className="h-5 w-5" /> Payout model</CardTitle>
            </CardHeader>
            <CardContent>
              <div className="overflow-x-auto">
                <table className="w-full text-left text-sm">
                  <thead className="text-gray-600">
                    <tr>
                      <th className="py-2">Tier</th>
                      <th className="py-2">Rate per 1,000 views</th>
                      <th className="py-2">When it applies</th>
                    </tr>
                  </thead>
                  <tbody className="divide-y">
                    <tr>
                      <td className="py-3 font-medium">Entry</td>
                      <td className="py-3">$0.50</td>
                      <td className="py-3">New collaborations and first 3 approved clips</td>
                    </tr>
                    <tr>
                      <td className="py-3 font-medium">Standard</td>
                      <td className="py-3">$1.25</td>
                      <td className="py-3">Most projects with quality and on time delivery</td>
                    </tr>
                    <tr>
                      <td className="py-3 font-medium">Pro</td>
                      <td className="py-3">$2.00</td>
                      <td className="py-3">High retention or repeat partnership performance</td>
                    </tr>
                  </tbody>
                </table>
              </div>
              <ul className="mt-4 text-sm text-gray-600 space-y-2">
                <li className="flex items-start gap-2"><Check className="h-4 w-4 mt-0.5" /> Minimum per approved clip, plus caps to prevent outlier risk</li>
                <li className="flex items-start gap-2"><Check className="h-4 w-4 mt-0.5" /> Retention bonus and fast turn bonus available</li>
                <li className="flex items-start gap-2"><Check className="h-4 w-4 mt-0.5" /> View window: 30 days from publish unless specified</li>
              </ul>
            </CardContent>
          </Card>
        </div>
      </section>

      {/* Standards */}
      <section className="mx-auto max-w-7xl px-6 py-14">
        <div className="grid lg:grid-cols-2 gap-10 items-center">
          <div>
            <h2 className="text-3xl font-semibold">Standards that make work easy</h2>
            <p className="mt-3 text-gray-700 max-w-prose">We keep training optional and focus on a short ruleset so your edits pass quickly. Style guide, safe zones, captions, and export specs are provided. QC is fast and fair.</p>
            <div className="mt-6 flex flex-wrap items-center gap-3">
              <Button className="rounded-2xl"><FileText className="mr-2 h-4 w-4" /> View standards</Button>
              <Button variant="outline" className="rounded-2xl">Preview export specs</Button>
            </div>
          </div>
          <Card className="rounded-2xl">
            <CardHeader>
              <CardTitle>What we check</CardTitle>
            </CardHeader>
            <CardContent>
              <ul className="space-y-2 text-sm text-gray-700">
                <li className="flex items-start gap-2"><Check className="h-4 w-4 mt-0.5" /> Hook clarity in first 2 seconds</li>
                <li className="flex items-start gap-2"><Check className="h-4 w-4 mt-0.5" /> Safe-zone and aspect compliance per platform</li>
                <li className="flex items-start gap-2"><Check className="h-4 w-4 mt-0.5" /> Caption readability and brand fonts</li>
                <li className="flex items-start gap-2"><Check className="h-4 w-4 mt-0.5" /> Clean audio and loudness match</li>
                <li className="flex items-start gap-2"><Check className="h-4 w-4 mt-0.5" /> Export preset matches brief</li>
              </ul>
            </CardContent>
          </Card>
        </div>
      </section>

      {/* FAQ */}
      <section className="mx-auto max-w-7xl px-6 pb-20">
        <div className="grid lg:grid-cols-2 gap-10 items-start">
          <div>
            <h2 className="text-3xl font-semibold">FAQ</h2>
            <div className="mt-6 space-y-6">
              <div>
                <h3 className="font-medium">Is the community free</h3>
                <p className="text-sm text-gray-600">Yes. There are no fees to join or apply. You only need to follow the standards on paying jobs.</p>
              </div>
              <div>
                <h3 className="font-medium">How do payouts work</h3>
                <p className="text-sm text-gray-600">We pay based on verified views during the agreed window. There is a minimum per approved clip, plus bonuses for retention and fast delivery. Rates vary by tier from $0.50 to $2.00 per 1,000 views.</p>
              </div>
              <div>
                <h3 className="font-medium">Do I have to take training</h3>
                <p className="text-sm text-gray-600">Training is optional. We focus on a short and clear standards checklist. If you want, there are quick refreshers for hooks, pacing, and captions.</p>
              </div>
            </div>
          </div>
          <Card className="rounded-2xl">
            <CardHeader>
              <CardTitle>Ready to join</CardTitle>
            </CardHeader>
            <CardContent>
              <p className="text-sm text-gray-600">Apply now and get matched to creators. Bring your style and speed. We bring briefs, structure, and payouts.</p>
              <div className="mt-4 flex gap-3">
                <Button className="rounded-2xl px-6">Apply now</Button>
                <Button variant="outline" className="rounded-2xl px-6">View sample brief</Button>
              </div>
            </CardContent>
          </Card>
        </div>
      </section>

      <footer className="border-t py-8 text-center text-sm text-gray-500">
        <p>Scale Suite © {new Date().getFullYear()} • Editors keep their IP for unused drafts</p>
      </footer>
    </div>
  );
}
